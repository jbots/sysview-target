segger_sysview_srcs = files([
  'SEGGER/SEGGER_SYSVIEW.c',
])

segger_sysview_incdirs = include_directories([
  'SEGGER',
])

segger_sysview_lib = static_library(
  'segger_sysview',
  [segger_sysview_srcs] ,
  c_args              : [c_args],
  include_directories : [config_incdirs, segger_sysview_incdirs]
)

