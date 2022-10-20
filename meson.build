project('multipart_parser_c', 'c',
  version : '0.1',
  default_options : ['warning_level=3'])

inc = include_directories('include')

subdir('include')
subdir('src')

multipart_parser_c_dep = declare_dependency(
  include_directories : inc,
  link_with : lib)
