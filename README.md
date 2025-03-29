# Envirz: A Simple Extension to chroot

Envirz is a script that simplifies the process of creating isolated environments, similar to `chroot`, but without the need to manually mount file systems. It provides an easy-to-use method for setting up and entering chroot-like environments with minimal effort.

## Features

- **Simplified Setup**: No need to manually mount file systems. Envirz handles it for you.
- **Isolated Environment**: Just like `chroot`, Envirz allows you to isolate the environment from the host system.
- **Easy to Use**: A straightforward script to quickly create and enter environments.

## Installation

To use Envirz, simply download the script and make it executable and copy it to /usr/bin/.

```
git clone https://github.com/Fundiman/envirz.git
cd envirz
chmod +x envirz
cp ./envirz /usr/bin/
```

## Usage

### Create and Enter Environment:
```
envirz.sh <path_to_chroot_directory>
```

This will automatically set up the chroot environment and enter it, bypassing the need to manually mount file systems.

### Exit the Environment:
Simply type `exit` to leave the isolated environment.

## Benefits Over chroot

- **No Mounting Required**: Automatically mounts necessary file systems for you.
- **Quick Setup**: One command to enter the environment.
- **Simplified Workflow**: Eliminates the usual hassle of managing chroot environments manually.

## License

Envirz is open-source software, released under the MIT License.
