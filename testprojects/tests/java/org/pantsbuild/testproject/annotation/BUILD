# Copyright 2015 Pants project contributors (see CONTRIBUTORS.md).
# Licensed under the Apache License, Version 2.0 (see LICENSE).


junit_tests(
  sources=['*'],
  dependencies=[
    '3rdparty:junit',
    # causes the `@Deprecated` annotation to result in a resource file during compilation
    'testprojects/src/java/org/pantsbuild/testproject/annotation/processor',
  ],
)
