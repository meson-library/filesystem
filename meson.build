project('filesystem', ['cpp'], 
         version         : '1.3.2',  
         license         : ['MIT'],
         meson_version   : '>= 0.49.0')




filesystem_dep = declare_dependency(
  include_directories: include_directories('include')
)




install_subdir('include/ghc', 
                install_dir : 'include')

install_data(['LICENSE'],
               rename      : ['LICENSE.MIT'],
               install_dir :  'share/licenses/filesystem')

if get_option('install_docs')
    install_data(['README.md'], install_dir :  'share/docs/filesystem')
endif