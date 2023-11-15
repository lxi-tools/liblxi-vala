lxitest_sources = [
  'main.vala',
  'receive-image-data.vala',
  'scpi.vala',
  'search-mdns.vala',
  'search.vala'
]

labui_deps = [
  dependency('glib-2.0'),
  dependency('liblxi'),
  meson.get_compiler('c').find_library('tirpc')
]

executable('liblxi_test', lxitest_sources,
  dependencies: labui_deps,
       install: true,
)