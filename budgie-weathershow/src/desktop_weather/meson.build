#configurationData = configuration_data()
#configurationData.set('PACKAGE_NAME', meson.project_name())
#configurationData.set('LOCALE_DIR', LOCALE_DIR)
#configure_file(input: 'config.h.in', output: 'config.h', configuration: configurationData)

#install_data('WeatherShow.plugin', install_dir: LIB_INSTALL_DIR)

DesktopWeatherSources = [
'desktop_weather.vala'
]

DesktopWeatherDependencies = [
dependency('gtk+-3.0'),
meson.get_compiler('c').find_library('m', required: false)
]

DesktopWeatherValaArgs = [
'--pkg=config',
'--vapidir=' + VAPI_DIR,
'--target-glib=2.38',
]

#DesktopWeatherCArgs = [
#'-include',
#'config.h',
#'-lm'
#]

DesktopWeatherCArgs = [
'-lm'
]

#shared_library(
#    'weathershow',
#    WeatherShowSources,
#    dependencies: WeatherShowDependencies,
#    vala_args: WeatherShowValaArgs,
#    c_args: WeatherShowCArgs,
#    install: true,
#    install_dir: LIB_INSTALL_DIR
#)


executable(
    'desktop_weather', DesktopWeatherSources,
    dependencies: DesktopWeatherDependencies,
    install: true,
    vala_args: DesktopWeatherValaArgs,
    c_args: DesktopWeatherCArgs,
    include_directories: config_inc_dir,
    install_dir: LIB_INSTALL_DIR,
)



