cxx_library(
  name = 'stockfish',
  header_namespace = 'stockfish',
  exported_headers = subdir_glob([
    ('src', '*.h'),
  ]),
  srcs = glob([
    'src/*.cpp',
  ],
  excludes = [
    'src/main.cpp',
  ]),
  compiler_flags = [
    '-std=c++14',
  ],
  visibility = [
    'PUBLIC',
  ],
)
