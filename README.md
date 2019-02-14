## Windows Subsystem

## Enable subsystem

```bash
Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux
```

## List network drive

```bash
net use
```

## Mount network drive

```bash
sudo mkdir /mnt/z
sudo mount -t drvfs Z: /mnt/z

sudo umount /mnt/z
```

## Issue

- https://github.com/Microsoft/WSL/issues/1954