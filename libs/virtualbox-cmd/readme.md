# Z1 Lib Virtualbox Cmd

Oracle Virtualbox macro


Documentation under construction.

## Usage

Install

```
yarn add @z1/lib-virtualbox-cmd
```

Import

```JavaScript

import * as virtualBox from '@z1/lib-virtualbox-cmd'

// gui: false will run the command headless
virtualBox.startCommand(vmName, { gui: true })
virtualBox.powerOffCommand(vmName)
virtualBox.listVMCommand()
virtualBox.listRunningCommand()
virtualBox.infoCommand(vmName)
virtualBox.setExtraDataCommand(vmName, key, value)

```
