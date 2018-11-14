prebuilt_cxx_library(
  name = 'throw-exception',
  header_only = True, 
  header_namespace = 'boost',
  exported_headers = subdir_glob([
    ('include/boost', '**/*.hpp'),
  ]),
  deps = [
    'buckaroo.github.buckaroo-pm.boost-config//:config', 
    'buckaroo.github.buckaroo-pm.boost-detail//:detail', 
    'buckaroo.github.buckaroo-pm.boost-exception//:exception', 
    'buckaroo.github.buckaroo-pm.boost-utility//:utility', 
  ], 
  visibility = [
    'PUBLIC',
  ],
)
