# INAOS CMake Build Utility
## API
### inac_enable_verbose
### inac_platform_libs_for_win LIBS
### inac_platform_libs_for_linux LIBS
### inac_platform_libs_for_unix LIBS
### function(inac_platform_libs_for_osx LIBS)
### function(inac_enable_sse4)
### function(inac_enable_aes)
### function(inac_enable_trace BUILD_TYPE LEVEL)
### function(inac_enable_log BUILD_TYPE LEVEL)
### function(inac_set_version major minor micro)
### function(inac_add_contrib_lib LIB)
### macro(inac_add_contrib_lib_win32 libname)
### macro(inac_add_contrib_lib_linux libname)
### macro(inac_add_contrib_lib_unix libname)
### macro(inac_add_contrib_lib_osx libname)
### function(inac_add_contrib_lib_ex TARGET)
### macro(inac_add_contrib_lib_ex_win32 TARGET)
### macro(inac_add_contrib_lib_ex_linux TARGET)
### macro(inac_add_contrib_lib_ex_unix TARGET)
### macro(inac_add_contrib_lib_ex_osx TARGET)
### function(inac_add_tests)
### function(inac_add_benchmarks)
### function(inac_add_tools)
### function(inac_post_copy_file TARGET FILE)
### macro(inac_post_copy_file_win32 TARGET FILE)
### macro(inac_post_copy_file_unix TARGET FILE)
### macro(inac_post_copy_file_osx TARGET FILE)
### macro(inac_post_copy_file_linux TARGET FILE)
### function(inac_merge_headers OUT_FILE)
### function(inac_add_contribs_headers)
### function(inac_add_luafiles TARGET)
### function(inac_merge_static_libs LIB)
### function(inac_artifact_repository LOCAL REMOTE [USRPWD user:password])
### function(inac_add_dependency name version)
### macro(inac_check_arch arch)
### function(inac_set_target_arch arch)
### function(inac_detect_host_arch)
### function (inac_make_package)
### function (inac_load_config_file PATH REQUIRED)
### function(inac_artifact_name name version output_var)
