# Sms

VB6 Systems Management Server toolkit bag: helpers for AD discovery, boundaries, DDR creation, service accounts, disk space, host type/time, ping, client-service restart, and SINV watch. Open any of the nested `.vbp` files (e.g. `ADDiscovery/ADDiscovery.vbp`) in the VB6 IDE.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `ADDiscovery` (`ADDiscovery/ADDiscovery.vbp`) | VB6 | WinForms exe | AD/SMS site server discovery |
| `Project1` (`Boundaries/Project1.vbp`) | VB6 | WinForms exe | SMS boundaries helper |
| `CreateDDR` (`CreateDDR/CreateDDR.vbp`) | VB6 | WinForms exe | Create SMS DDR records |
| `CreateServiceAccounts` (`CreateServiceAccounts/CreateServiceAccounts.vbp`) | VB6 | WinForms exe | Create SMS service accounts |
| `WMIDiskSpace` (`Diskspace/DiskSpace.vbp`) | VB6 | WinForms exe | WMI disk space check |
| `GetHostsType` (`GetHostsType/GetHostsType.vbp`) | VB6 | WinForms exe | Host type probe |
| `Hosttime` (`Hosttime/Hosttime.vbp`) | VB6 | WinForms exe | Remote host time |
| `HostType` (`Hosttype/Hosttype.vbp`) | VB6 | WinForms exe | Host type classifier |
| `PingHosts` (`PingHosts/PingHosts.vbp`) | VB6 | WinForms exe | Ping host list |
| `PingServers` (`PingServers/PingServers.vbp`) | VB6 | WinForms exe | Ping SMS servers |
| `RestartClientService` (`Restart Client Service/RestartClientService.vbp`) | VB6 | WinForms exe | Restart SMS client service |
| `SinvWatcher` (`Sinv Watcher/Sinv Watcher.vbp`) | VB6 | WinForms exe | Software inventory watcher |
