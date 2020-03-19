[IntelliJ Platform SDK Code Samples](../README.md)

# Module Type Sample Project

## Quickstart

TODO

## Structure

The plugin was developed using the [IntelliJ Platform SDK][docs_sdk].

The main file is [plugin.xml][plugin.xml], which is created accordingly to the [Plugin Configuration File documentation][docs_pluginxml].
It describes definitions of the actions, extensions, or listeners provided by the plugin:

### Extension Points

| Name | Implementation Class | Interface |
| ---- | -------------------- | --------- |
| moduleType | [DemoModuleType][moduleType_implementation] | [ModuleType][moduleType_interface] |

[Extension Points documentation][docs_ep]

## Function

TODO

[plugin.xml]: ./src/main/resources/META-INF/plugin.xml
[docs_tool_windows]: https://www.jetbrains.org/intellij/sdk/docs/user_interface_components/tool_windows.html
[docs_pluginxml]: https://www.jetbrains.org/intellij/sdk/docs/basics/plugin_structure/plugin_configuration_file.html
[docs_sdk]: https://www.jetbrains.org/intellij/sdk/docs/intro/about.html
[docs_ep]: https://www.jetbrains.org/intellij/sdk/docs/basics/plugin_structure/plugin_extension_points.html
[docs_run]: https://www.jetbrains.org/intellij/sdk/docs/tutorials/build_system/prerequisites.html#running-a-simple-gradle-based-intellij-platform-plugin

[moduleType_implementation]: ./src/main/java/org/intellij/sdk/module/DemoModuleType.java
[moduleType_interface]: https://github.com/JetBrains/intellij-community/blob/master/platform/lang-api/src/com/intellij/openapi/module/ModuleType.java