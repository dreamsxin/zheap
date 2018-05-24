Zheap Part I: Undo Log Storage

This branch is maintained by a robot.  It is automatically filtered and
combined from the commit history in the zheap-tmunro branch at
at https://github.com/EnterpriseDB/zheap into a more presentable form.
It's a preview of the lowest level patch-set in the Zheap proposal.
It's work in progress.

There are four patches in this patch set:

* [0001-Add-undo-log-manager.patch](../../commit/fd72cc0ab7850a2ee3f546da8222389ce9cecabf)
* [0002-Provide-access-to-undo-log-data-via-the-buffer-manager.patch](../../commit/24129934c491179edcdd02c6085d74074ecb702c)
* [0003-Add-developer-documentation-for-the-undo-log-manager.patch](../../commit/957ef431a6a14afe1b387b47fa1e60facda537f5)
* [0004-Add-tests-for-the-undo-log-manager.patch](../../commit/c5ca93c3bb759079c81aac3b507a5834864506c2)
* [0005-Add-user-facing-documentation-for-undo-logs.patch](../../commit/fa025401a5bc487384b628099ca2c03e4962459d)

This branch is automatically tested by:

* Ubuntu build bot over at Travis CI:  [<img src="https://travis-ci.org/macdice/postgres.svg?branch=undo-log-storage"/>](https://travis-ci.org/macdice/postgres/branches)
* Windows build bot over at AppVeyor: [<img src="https://ci.appveyor.com/api/projects/status/github/macdice?branch=undo-log-storage&svg=true"/>](https://ci.appveyor.com/project/macdice/postgres/branch/undo-log-storage)

