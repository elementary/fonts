project(
    'fonts',
    version: '5.1.0'
)

conf_avail_dir = get_option('sysconfdir') / 'fonts' / 'conf.avail'
fonts_dir = get_option('datadir') / 'fonts' / 'truetype'

install_data(
    '31-croscore-elementary.conf',
    install_dir: conf_avail_dir
)

install_symlink(
    '31-croscore-elementary.conf',
    install_dir: get_option('sysconfdir') / 'fonts' / 'conf.d',
    pointing_to: conf_avail_dir / '31-croscore-elementary.conf'
)

subdir('redacted')
subdir('roboto-mono')
