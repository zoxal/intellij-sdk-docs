[IntelliJ Platform SDK Code Samples](../README.md)

# PyCharm Sample Project

## Quickstart

TODO

## Structure

The plugin was developed using the [IntelliJ Platform SDK][docs_sdk].

The main file is [plugin.xml][plugin.xml], which is created accordingly to the [Plugin Configuration File documentation][docs_pluginxml].
It describes definitions of the actions, extensions, or listeners provided by the plugin:

### Actions

| Name | Implementation Class | Interface |
| ---- | -------------------- | --------- |
| PopupDialogAction | [PopupDialogAction][PopupDialogAction_implementation] | [AnAction][PopupDialogAction_interface] |

[Actions documentation][docs_actions]

## Function

TODO

[plugin.xml]: ./src/main/resources/META-INF/plugin.xml
[docs_tool_windows]: https://www.jetbrains.org/intellij/sdk/docs/user_interface_components/tool_windows.html
[docs_pluginxml]: https://www.jetbrains.org/intellij/sdk/docs/basics/plugin_structure/plugin_configuration_file.html
[docs_sdk]: https://www.jetbrains.org/intellij/sdk/docs/intro/about.html
[docs_actions]: https://www.jetbrains.org/intellij/sdk/docs/basics/action_system.html
[docs_run]: https://www.jetbrains.org/intellij/sdk/docs/tutorials/build_system/prerequisites.html#running-a-simple-gradle-based-intellij-platform-plugin

[PopupDialogAction_implementation]: ./src/main/java/com/intellij/sdk/pycharm/PopupDialogAction.java
[PopupDialogAction_interface]: https://github.com/JetBrains/intellij-community/blob/master/platform/editor-ui-api/src/com/intellij/openapi/actionSystem/AnAction.java