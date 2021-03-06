
# CHANGELOG

## 2.1.0 - 2020-02-07

- NEW: Support for incremental build mode in Gradle
- FIX: Class fields are not serialized in case both class and its subclass are @AutoSerializable (#3)
- FIX: writeInline method breaks compilation if classes in hierarchy have the same name (#4)

## 2.0.1 - 2015-12-04

- FIX: @Ordinal causes compile error if marked field is of nested class

## 2.0.0 - 2015-09-02

- NEW: Java 8 support
- FIX: Fields of @AutoSerializable classes should be transient
- FIX: EGEN annotation is not processed in combination with other if it isn't on the first place
- FIX: EGEN exceptions are not reported in `egen_output.txt`   

**NOTE:** Java 7 support dropped

## 1.0.2 - 2015-08-05

Initial public version
