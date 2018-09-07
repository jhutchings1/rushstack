[Home](./index) &gt; [@microsoft/ts-command-line](./ts-command-line.md) &gt; [ICommandLineActionOptions](./ts-command-line.icommandlineactionoptions.md)

# ICommandLineActionOptions interface

Options for the CommandLineAction constructor.

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [`actionName`](./ts-command-line.icommandlineactionoptions.actionname.md) | `string` | The name of the action. For example, if the tool is called "example", then the "build" action might be invoked as: "example build -q --some-other-option" |
|  [`documentation`](./ts-command-line.icommandlineactionoptions.documentation.md) | `string` | A detailed description that is shown on the action help page, which is displayed by the command "example build --help", e.g. for actionName="build". |
|  [`summary`](./ts-command-line.icommandlineactionoptions.summary.md) | `string` | A quick summary that is shown on the main help page, which is displayed by the command "example --help" |
