project('SDL Template', 'cpp', version: '1.0.0', default_options : ['default_library=static','cpp_std=c++17',])

sdl2_dep = dependency('sdl2')
sdl2_image_dep = dependency('SDL2_image')
sdl2_mixer_dep = dependency('SDL2_mixer')

incdir = include_directories('include')

src = [
    
    'src/main.cc',
    'src/core/core.cc'
]

executable('SDLTemplate', src, dependencies : [sdl2_image_dep, sdl2_mixer_dep, sdl2_dep], include_directories : incdir)
