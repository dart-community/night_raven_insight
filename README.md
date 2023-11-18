An opinionated analysis configuration that aims to
enable insightful analysis of your packages.

## Enable analysis

To use `package:night_raven_insight` as your
package's base analysis configuration,
first add it as a dev dependency in your `pubspec.yaml` file:

```shell
dart pub add dev:night_raven_insight
```

Then, specify it as the value of the `include` field
in your `analysis_options.yaml` file:

```yaml
include: package:night_raven_insight/analysis_options.yaml
```

## Learn more

To learn more about the options this package enables and
other analysis options, check out [Customizing static analysis][] and
the list of all [linter rules][] that Dart provides.

[Customizing static analysis]: https://dart.dev/tools/analysis
[linter rules]: https://dart.dev/lints
