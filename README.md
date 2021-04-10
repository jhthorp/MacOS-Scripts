# MacOS Scripts

The scripts within this project are to support various useful operations on a 
system running MacOS.

## Table of Contents

* [Warnings](#warnings)
* [Getting Started](#getting-started)
* [Prerequisites](#prerequisites)
* [Setup](#setup)
* [Scripts](#scripts)
	* [Commands](#commands)
		* [run_as_admin.sh](#run_as_adminsh)
		* [run_as_user.sh](#run_as_usersh)
	* [Data](#data)
		* [list_drives.sh](#list_drivessh)
	* [Imaging](#imaging)
		* [burn_iso_to_drive.sh](#burn_iso_to_drivesh)
* [Deployment](#deployment)
* [Dependencies](#dependencies)
* [Notes](#notes)
* [Test Environments](#test-environments)
	* [Operating System Compatibility](#operating-system-compatibility)
	* [Hardware Compatibility](#hardware-compatibility)
* [Contributing](#contributing)
* [Support](#support)
* [Versioning](#versioning)
* [Authors](#authors)
* [Copyright](#copyright)
* [License](#license)
* [Acknowledgments](#acknowledgments)

## Warnings

| :warning: |                      :warning:                       | :warning: |
|   :---:   |                        :---:                         |   :---:   |
| :warning: |   **Executing Imaging scripts may destroy data!**    | :warning: |
| :warning: |                      :warning:                       | :warning: |

## Getting Started

These instructions will get you a copy of the project up and running on your 
local machine for development and testing purposes. See 
[deployment](#deployment) for notes on how to deploy the project on a live 
system.

### Prerequisites

* [Utility-Scripts](https://github.com/jhthorp/Utility-Scripts) exist at the 
same directory path

### Setup

In order to use the scripts within this package, you will need to clone, or 
download, the [Utility-Scripts](https://github.com/jhthorp/Utility-Scripts) 
repository into the same top-level directory path.

```
/path/to/Utility-Scripts
/path/to/MacOS-Scripts
```

## Scripts

### Commands

#### run_as_admin.sh

A script to execute a command as the administrator.

_Usage_

```
[bash] ./run_as_admin.sh <cmd>
```

_Options_

| Option Flag |                          Description                           |
|    :---:    |                             :---:                              |
|     N/A     |                              N/A                               |

_Parameters_

|         Parameter         |                   Description                    |
|           :---:           |                      :---:                       |
|          Command          |                  Command to run                  |

_Examples_

* **./run_as_admin.sh** "pwd"

#### run_as_user.sh

A script to execute a command as a specific user.

_Usage_

```
[bash] ./run_as_user.sh <user> <cmd>
```

_Options_

| Option Flag |                          Description                           |
|    :---:    |                             :---:                              |
|     N/A     |                              N/A                               |

_Parameters_

|         Parameter         |                   Description                    |
|           :---:           |                      :---:                       |
|           User            |            User to run the command as            |
|          Command          |                  Command to run                  |

_Examples_

* **./run_as_user.sh** "user" "pwd"

### Data

#### list_drives.sh

A script to list all available drives.

_Usage_

```
[bash] ./list_drives.sh
```

_Options_

| Option Flag |                          Description                           |
|    :---:    |                             :---:                              |
|     N/A     |                              N/A                               |

_Parameters_

|         Parameter         |                   Description                    |
|           :---:           |                      :---:                       |
|            N/A            |                       N/A                        |

_Examples_

* **./list_drives.sh**

### Imaging

#### burn_iso_to_drive.sh

A script to burn an ISO image onto a chosen drive.

_Usage_

```
[bash] ./burn_iso_to_drive.sh <iso_file> <drive_id>
```

_Options_

| Option Flag |                          Description                           |
|    :---:    |                             :---:                              |
|     N/A     |                              N/A                               |

_Parameters_

|         Parameter         |                   Description                    |
|           :---:           |                      :---:                       |
|         ISO File          |          ISO image to burn to the drive          |
|         Drive ID          |       Drive ID to burn the ISO image onto        |

_Examples_

* **./burn_iso_to_drive.sh** "~/Documents/test_iso.iso" "da3"

_Drives Tested_

|        Status        |                       Component                       |
|        :---:         |                         :---:                         |
|  :white_check_mark:  |       Sandisk Ultra USB 2.0 Flash Drive (32GB)        |
|  :white_check_mark:  |       Sandisk Ultra USB 3.0 Flash Drive (32GB)        |

## Deployment

This section provides additional notes about how to deploy this on a live 
system.

## Dependencies

* [Utility-Scripts](https://github.com/jhthorp/Utility-Scripts) - A collection 
of utility scripts.

## Notes

This project does not contain any additional notes at this time.

## Test Environments

### Operating System Compatibility

|        Status        |                        System                         |
|        :---:         |                         :---:                         |
|  :white_check_mark:  |                     MacOS 11.2.x                      |
|  :white_check_mark:  |                     MacOS 11.1.x                      |
|  :white_check_mark:  |                     MacOS 11.0.x                      |

### Hardware Compatibility

|        Status        |                       Component                       |
|        :---:         |                         :---:                         |
|  :white_check_mark:  |              MacBook Pro (15-inch, 2018)              |

## Contributing

Please read [CODE_OF_CONDUCT](.github/CODE_OF_CONDUCT.md) for details on our 
Code of Conduct and [CONTRIBUTING](.github/CONTRIBUTING.md) for details on the 
process for submitting pull requests.

## Support

Please read [SUPPORT](.github/SUPPORT.md) for details on how to request 
support from the team.  For any security concerns, please read 
[SECURITY](.github/SECURITY.md) for our related process.

## Versioning

We use [Semantic Versioning](http://semver.org/) for versioning. For available 
releases, please see the 
[available tags](https://github.com/jhthorp/MacOS-Scripts/tags) or look through 
our [Release Notes](.github/RELEASE_NOTES.md). For extensive documentation of 
changes between releases, please see the [Changelog](.github/CHANGELOG.md).

## Authors

* **Jack Thorp** - *Initial work* - [jhthorp](https://github.com/jhthorp)

See also the list of 
[contributors](https://github.com/jhthorp/MacOS-Scripts/contributors) who 
participated in this project.

## Copyright

Copyright © 2020 - 2021, Jack Thorp and associated contributors.

## License

This project is licensed under the GNU General Public License - see the 
[LICENSE](LICENSE.md) for details.

## Acknowledgments

* N/A