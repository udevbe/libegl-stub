libeglstub = library(
    'libegl',
    sources: [ 'stub.c' ],
    version: '1.4',
    install: true,
    include_directories: libeglstub_inc,
)

pkg = import('pkgconfig')
pkg.generate(
    libraries: libeglstub,
    name: 'EGL',
    description: 'EGL stub library and headers',
    version: meson.project_version(),
    filebase: 'egl'
)