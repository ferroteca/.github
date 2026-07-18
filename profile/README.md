# ferroteca

Running legacy and retro computing platforms under emulation and virtualization.

Projects here provide the plumbing that makes old software and hardware runnable again — drivers and I/O layers for guest platforms, and automation to drive and control those guests programmatically. Testing infrastructure rounds it out, verifying that everything keeps working.

## Projects

| Repo | What it does |
| --- | --- |
| [`virtio-dos`](https://github.com/ferroteca/virtio-dos) | virtio drivers for DOS VM guests — modern storage/network I/O instead of legacy emulated hardware |
| [`quemados`](https://github.com/ferroteca/quemados) | DOS-under-QEMU automation harness — boots, drives, and controls DOS guests programmatically |
| [`testaferro`](https://github.com/ferroteca/testaferro) | A pytest facade for VM guest-executed unit testing |

## License

Most ferroteca projects are BSD 3-Clause licensed — see individual repos for details.
