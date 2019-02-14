## Windows Subsystem

## Enable Subsystem

```bash
Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux
```

## List Network Drive

```bash
net use
```

## Mount Network Drive

```bash
sudo mkdir /mnt/z
sudo mount -t drvfs Z: /mnt/z

sudo umount /mnt/z
```

## Issue

- https://github.com/Microsoft/WSL/issues/1954