# Copyright 2019 Pants project contributors (see CONTRIBUTORS.md).
# Licensed under the Apache License, Version 2.0 (see LICENSE).

files(
  name = 'build_file_imports_function_directory',
  sources = rglobs('build_file_imports_function/*'),
)

files(
  name = 'build_file_imports_module_directory',
  sources = rglobs('build_file_imports_module/*'),
)

files(
  name = 'python_targets_directory',
  sources = rglobs('python_targets/*'),
  dependencies = [
    'testprojects/src/python/python_targets:test',
  ],
)

files(
  name = 'unicode_directory',
  sources = rglobs('unicode/*'),
)