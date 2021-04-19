project('triumphal-backgrounds',
          version: '0.1.0',
    meson_version: '>= 0.50.0',
  default_options: [ 'warning_level=2',
                   ],
  license: 'GPL-3.0-or-later',
)

backgrounds = [
    'images/Arc_de_Triomphe.png',
]

install_data(backgrounds, install_dir: '/usr/share/backgrounds/triumphal/')
install_data('triumphal-backgrounds.xml', install_dir: '/usr/share/gnome-background-properties/')
