project('webfontkitgenerator',
          version: '1.0.2',
    meson_version: '>= 0.50.0',
  default_options: [ 'warning_level=2',
                   ],
)

i18n = import('i18n')

subdir('data')
subdir('webfontkitgenerator')
subdir('po')

meson.add_install_script('build-aux/meson/postinstall.py')
