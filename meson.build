project('winmin-viewer', 'c')

deps = [
  dependency('gio-2.0', version: '>= 2.50'),
  dependency('gtk+-3.0', version: '>= 3.22'),
  dependency('spice-client-gtk-3.0'),
]

executable('winmin-viewer', 'winmin-viewer.c',
  dependencies: deps,
  install: true, install_dir : '/usr/bin',
)
