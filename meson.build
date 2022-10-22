project('md4c', 'c',
  version: '0.4.8',
  meson_version: '>=0.63.0',
  default_options : [
    'warning_level=1',
    'default_library=shared'])

includes = include_directories(['src'])

libmd4c = library('md4c',
    'src/md4c.c',
    include_directories: includes)

md4c_dep = declare_dependency(
  link_with: libmd4c,
  include_directories: [includes])
