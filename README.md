# Log4Pascal

Log4pascal is an Open Source project that aims to produce a simple logging suite for ObjectPascal (Delphi, FreePascal).
Log4Pascal is NOT based on the Log4J package from the Apache Software Foundation. Well, just the name.

## How to use

Just add the unit "src/Log4Pascal.pas" to project.
  - ``Project -> Add to Project`` and then locate and choose the file.

### Example

```delphi
Logger.Msg('Normal message log');
Logger.Error('Error message log');
Logger.Warning('Warning message log');
```

```delphi
Logger.Debug('Message is logged only when in debug');
```

## License

This software is open source, licensed under the The MIT License (MIT). See [LICENSE](https://github.com/martinusso/log4pascal/blob/master/LICENSE) for details.