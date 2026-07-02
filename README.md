# ObjC Runtime Dumper

A lightweight Objective-C runtime dumper for iOS applications.

Dump Objective-C classes, methods, ivars, and properties directly from runtime into a generated `OBJCDump.h` header file.

---


## Features

- Dump Objective-C runtime information
- Generate `OBJCDump.h`
- Search applications by name or bundle identifier
- Support Jailbreak & Non-Jailbreak
- Per-app enable/disable
- Lightweight & fast

---

## Output

Generated dump file:

```objc
OBJCDump.h
```

Contains:

- Classes
- Ivars
- Methods
- Properties
- Protocols
- Structs
- Addresses

---

## Supported Apps

Works well with many games and applications such as:

- 8 Ball Pool
- Most Objective-C based applications

---
### Download files from the Releases section.

<p align="center">
  <a href="https://github.com/giangbeoios/ObjC-Runtime-Dumper/releases">
    <img src="https://img.shields.io/badge/Download-Releases-2ea44f?style=for-the-badge&logo=github" />
  </a>
</p>

## Jailbreak Version

### Requirements

Install tweak:

- PreferenceLoader

Then install the `.deb` package.

After installation:

```text
Settings -> ObjC Runtime Dumper
```

You can enable or disable dumping for specific apps directly from Preferences.

---

## Non-Jailbreak Version

For non-jailbreak devices:

- Inject the `.dylib` into the target application
- Launch the application
- Dump file will be generated automatically

Compatible with common Trollfools/Sideloady/Esign/Gbox/Injection tools...

---

## Known Issues

This project is still under development.

Some applications may:

- Freeze during runtime scanning
- Some structs may be incomplete, incorrect, or missing fields
- Some data types may not be fully resolved

---

## Limitations

- Freeze during runtime scanning
- Does NOT support Apple system applications
- Some protected apps may block runtime access
- Swift-only applications may provide limited results

---

## Author

- [GiangBeoIOS](https://github.com/giangbeoios)

---

## Disclaimer

This project is for educational and research purposes only.
