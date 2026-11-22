# note-definitions_PXM 0.40.9

- 移除保存词条时自动修改其他 shard 的逻辑，避免与正在进行的写入产生 Definition shard changed before write。
