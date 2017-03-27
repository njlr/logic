include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'logic',
  header_only = True,
  header_namespace = 'boost/logic',
  exported_headers = subdir_glob([
    ('include/boost/logic', '**/*.hpp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
