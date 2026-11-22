# note-definitions_PXM 0.41.0

- 词条写入后 4 秒内暂停后台 shard 自动修复，避免连续两次保存时 repairMisplaced 与写入竞争触发 Definition shard changed before write。
