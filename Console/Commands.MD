###### Taken from Steam Client Win64 Beta 1498032887 built Nov 1 2016, at 12:01:19

```
apps_installed -
apps_running - displays information about running games tracked by Steam
app_backup - <appId> <max size MB> <target folder>
app_dlc_status - app_status <appId> <dlcId>
app_download_enable - <0|1>
app_info_http_min = "0" -
app_info_http_num_sockets = "8" -
app_info_print - Dumps app info for appID
app_info_update - [0|1] : trigger app info update, optionally for update all
app_install - <appId> [volumeindex]
app_license_request - <AppID> - Requests a free licenses for this app if not already owned.
app_mark_validation - <appId> <0|1:full>
app_restore - <appId> <backup folder>
app_set_update_flag - app_set_update_flag <appId>
app_start_validation - <appId>
app_status - app_status <appId>
app_stop - <appid> [force:0|1] stop this running app
app_uninstall - [-complete] <appId>
app_update_cancel - <EAppUpdateError>
async_disconnect - async disconnect
bigpicturetips_enableinvisibletips = "0" -
bigpicturetips_enableseentips = "0" -
broadcast_adjust_bitrate = "200" -
broadcast_upload_drop_sec = "6" -
broadcast_upload_update_sec = "3" -
build_installer - <project file> <target folder> [beta key] [beta pwd]
clear_console - Clears console text
clear_marketing_message_views - Refetches & displays all marketing messages, ignoring the list of those already seen
cloud_sync_down - <appid> Manually triggers UFS to download files for the given app.
cloud_sync_up - <appid> Manually triggers UFS to upload files for the given app.
cm_force_change - Change CM List
config_refresh - Refresh client configuration
connect_remote - <ip:port>
device_authorize_local - <description> : authorize local device for authorized users
device_authorize_status - prints device authorization status
device_deauthorize_local - deauthorize local device for all users
disable_license - <packagid> Temporarily disables a license that was granted through the Steamworks site
download_depot - download_depot <appid> <depotid> [<target manifestid>] [<delta manifestid>] [<depot flags filter>] : download a single depot
download_item - download_item <appid> <PublishedFileId> : download a workshop item
download_sources - Dumps list of download sources
dump_scheduled_functions - usage: "dump_scheduled_functions" Displays internal Steam function callback timers
enable_license - <packagid> Enables a previously disabled license that was granted through the Steamworks site
get_download_throttle -
html_exit_fullscreen - If the web panel for the ui is currently fullscreen, undo that
install_folder_add - <path>
install_folder_list - list all mounted Steam volumes
install_folder_ui - show UI dialog
join_steam_use_web = "0" -
kv_stats - Render KeyValues stats
library_sharing_account_max = "5" -
licenses_for_app - <appid> : shows active licenses for appid
licenses_print - display users's Steam3 licenses
log_callbacks - usage: "log_callbacks <first callbackID> [last callbackID]
log_files_always_flush = "0" -
log_ipc - usage: "log_ipc [counts|verbose] <filter>" Enables IPC logging. Specifying "counts" or "verbose" is optional, defaulting to counts.
log_matchmaking_callbacks = "0" -
manage_steamguard_useweb = "0" -
manifest_dump - <filename>
mem_stats - Dump memory stats
mem_validate - <dump|leaks> <threshold> : validates memory
mem_walk - [full] : validates memory
MergeCapReprocess_minutes = "480" -
mic_autogain = "16000" - automatic gain control level for microphone input
mic_inputfile = "" - causes voice data to be read from the specified file instead of from the microphone
mic_outputfile = "" - causes microphone data to be written out to the specified file
minidump_assert - generates an assert
minidump_crash - crashes the Steam client
net_incomingcheck = "1" -
net_maxresendsperframe = "32" -
net_msgdump - Dumps list of sent net messages
net_msgspew - Spews sent net messages
p2p_connecttimeout = "15" -
p2p_info - usage: "p2p_info" Displays the current state of the P2P networking subsystem.
p2p_unusedtimeout = "120" -
package_info_print - Dumps package info for packageID
panorama_upload_mappings = "0" -
profile_dump - Tells vprof to dump the full profile of all threads (using the last profile data if vprof is off)
profile_off - Turns off vprof and halts profiling
profile_on - Turns on vprof and begins profiling
profile_on_dump_spikes - Turns on vprof, and enables automatic dumping of any single frame that contains spikes above the given threshold in milliseconds (use the regular profile_off to stop)
profile_show_gui - Tells UI to pop a profile dialog for each known thread, must use profile_on/off separately to actually enable/disable data gathering
render_ipc_connections - usage: "render_ipc_connections
sc_kalman_a_vel = "1.0" -
sc_kalman_fastq = "0" -
sc_kalman_h_vel = "1.0" -
sc_kalman_q_vel = "2.0" -
sc_kalman_r_vel = "2.0" -
sc_kalman_slowq = "0" -
service_repair - Repair Steam service
service_restart - Restarts Steam Windows service
service_test - Test Steam service
set_download_throttle - set_download_throttle <kbps> <bPersistent = false>
set_spew - <group> <spewlevel> <loglevel> Sets spew and log levels for a given group
set_spew_level - <SpewLevel LogLevel> Sets spew and log levels for all groups
spew_controller_loss = "0" -
stats_dump - stats_dump [filter] : dumps matching debug stats
stats_gui - stats_gui : show debug stats panel
stats_monitor - stats_monitor <stat name> [rate] [KB|MB] : monitor a debug stat value
stats_reset - stats_reset [filter] : set matching stats back to 0
steamcontroller_developer = "0" -
streaming_log_spikes = "0" -
tenfoot_forcelaunchgameid = "0" -  games no friends, 3 - some games and friends, 4 - some  friends no games
tenfoot_match - [prefix]: matches a string prefix
tenfoot_pickle_dictionaries - compiles daisy wheel input dictionaries to more performant form
tenfoot_pickle_single_dictionary - [language] compiles one daisy wheel input dictionary
tenfoot_text_hotspots - find text autosuggest hot spots
test_dropcon - Tests dropping a connection
test_failnextconnect - Tests failing the next connection
user_friends - Dumps list of friends
user_info - Dump various Steam info
verify_chunk_store - verify_chunk_store <appid> <depotid> <datafile> : run app depot build as specified in appbuildfile
vgui_spewpanelstats - spew active panel stats
voice_autogain = "0" -
voice_game_usage - displays information about the game's use of Steam voice
voice_minabs = "0.15" -
voice_minavg = "1.0" -
voice_outputdevice = "0" - 0=>Miles 1=>XAudio2
voice_outputfile = "" - causes output from voice system to be written out to the specified file
voice_preprocess = "1" - enables voice cleanup on incoming microphone data
voice_quality = "4" -
windows_info - system_info : prints system information
workshop_download_item - workshop_download_item <appid> <PublishedFileId> : download a workshop item
workshop_items_cache_days = "14" -
workshop_items_update_interval = "900" -
workshop_status - workshop_status <appId>
```
