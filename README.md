cvar list
--------------
_autosave                                : cmd      :                  : Autosave
_autosavedangerous                       : cmd      :                  : AutoSaveDangerous
_bugreporter_restart                     : cmd      :                  : Restarts bug reporter .dll
_resetgamestats                          : cmd      :                  : Erases current game stats and writes out a blank stats file
_restart                                 : cmd      :                  : Shutdown and restart the engine.
achievement_debug                        : 0        : , "sv", "cheat", "rep" : Turn on achievement debug msgs.
addip                                    : cmd      :                  : Add an IP address to the ban list.
adsp_alley_min                           : 122      :                  :
adsp_courtyard_min                       : 126      :                  :
adsp_debug                               : 0        : , "a"            :
adsp_door_height                         : 112      :                  :
adsp_duct_min                            : 106      :                  :
adsp_hall_min                            : 110      :                  :
adsp_low_ceiling                         : 108      :                  :
adsp_opencourtyard_min                   : 126      :                  :
adsp_openspace_min                       : 130      :                  :
adsp_openstreet_min                      : 118      :                  :
adsp_openwall_min                        : 130      :                  :
adsp_room_min                            : 102      :                  :
adsp_street_min                          : 118      :                  :
adsp_tunnel_min                          : 114      :                  :
adsp_wall_height                         : 128      :                  :
ai_auto_contact_solver                   : 1        : , "sv"           :
ai_block_damage                          : 0        : , "sv"           :
ai_debug_assault                         : 0        : , "sv"           :
ai_debug_avoidancebounds                 : 0        : , "sv"           :
ai_debug_directnavprobe                  : 0        : , "sv"           :
ai_debug_doors                           : 0        : , "sv"           :
ai_debug_dyninteractions                 : 0        : , "sv"           : Debug the NPC dynamic interaction system.
ai_debug_efficiency                      : 0        : , "sv"           :
ai_debug_enemies                         : 0        : , "sv"           :
ai_debug_expressions                     : 0        : , "sv"           : Show random expression decisions for NPCs.
ai_debug_follow                          : 0        : , "sv"           :
ai_debug_loners                          : 0        : , "sv"           :
ai_debug_looktargets                     : 0        : , "sv"           :
ai_debug_los                             : 0        : , "sv", "cheat"  : NPC Line-Of-Sight debug mode. If 1, solid entities that block NPC LOC will be highlighted with white bounding boxes. If 2, it'll show non-solid entities that would do it if they were solid.
ai_debug_nav                             : 0        : , "sv"           :
ai_debug_node_connect                    : cmd      :                  : Debug the attempted connection between two nodes
ai_debug_ragdoll_magnets                 : 0        : , "sv"           :
ai_debug_shoot_positions                 : 0        : , "sv", "cheat", "rep" :
ai_debug_speech                          : 0        : , "sv"           :
ai_debug_squads                          : 0        : , "sv"           :
ai_debug_think_ticks                     : 0        : , "sv"           :
ai_debugscriptconditions                 : 0        : , "sv"           :
ai_default_efficient                     : 0        : , "sv"           :
ai_drawbattlelines                       : 0        : , "sv", "cheat"  :
ai_drop_hint                             : cmd      :                  : Drop an ai_hint at the player's current eye position.
ai_dump_hints                            : cmd      :                  :
ai_efficiency_override                   : 0        : , "sv"           :
ai_enable_fear_behavior                  : 1        : , "sv"           :
ai_expression_frametime                  : 0        : , "sv"           : Maximum frametime to still play background expressions.
ai_expression_optimization               : 0        : , "sv"           : Disable npc background expressions when you can't see them.
ai_fear_player_dist                      : 720      : , "sv"           :
ai_find_lateral_cover                    : 1        : , "sv"           :
ai_find_lateral_los                      : 1        : , "sv"           :
ai_follow_use_points                     : 1        : , "sv"           :
ai_follow_use_points_when_moving         : 1        : , "sv"           :
ai_force_serverside_ragdoll              : 0        : , "sv"           :
ai_frametime_limit                       : 50       : , "sv"           : frametime limit for min efficiency AIE_NORMAL (in sec's).
ai_lead_time                             : 0        : , "sv"           :
ai_LOS_mode                              : 0        : , "sv", "rep"    :
ai_moveprobe_debug                       : 0        : , "sv"           :
ai_moveprobe_jump_debug                  : 0        : , "sv"           :
ai_moveprobe_usetracelist                : 0        : , "sv"           :
ai_navigator_generate_spikes             : 0        : , "sv"           :
ai_navigator_generate_spikes_strength    : 8        : , "sv"           :
ai_no_local_paths                        : 0        : , "sv"           :
ai_no_node_cache                         : 0        : , "sv"           :
ai_no_select_box                         : 0        : , "sv"           :
ai_no_steer                              : 0        : , "sv"           :
ai_no_talk_delay                         : 0        : , "sv"           :
ai_norebuildgraph                        : 0        : , "sv"           :
ai_path_adjust_speed_on_immediate_turns  : 1        : , "sv"           :
ai_path_insert_pause_at_est_end          : 1        : , "sv"           :
ai_path_insert_pause_at_obstruction      : 1        : , "sv"           :
ai_post_frame_navigation                 : 0        : , "sv"           :
ai_radial_max_link_dist                  : 512      : , "sv"           :
ai_reaction_delay_alert                  : 0        : , "sv"           :
ai_reaction_delay_idle                   : 0        : , "sv"           :
ai_rebalance_thinks                      : 1        : , "sv"           :
ai_report_task_timings_on_limit          : 0        : , "a", "sv"      :
ai_sequence_debug                        : 0        : , "sv"           :
ai_set_move_height_epsilon               : cmd      :                  : Set how high AI bumps up ground walkers when checking steps
ai_setupbones_debug                      : 0        : , "sv"           : Shows that bones that are setup every think
ai_shot_bias                             : 1        : , "sv"           :
ai_shot_bias_max                         : 1        : , "sv", "rep"    :
ai_shot_bias_min                         : -1       : , "sv", "rep"    :
ai_shot_stats                            : 0        : , "sv"           :
ai_shot_stats_term                       : 1000     : , "sv"           :
ai_show_hull_attacks                     : 0        : , "sv"           :
ai_show_think_tolerance                  : 0        : , "sv"           :
ai_simulate_task_overtime                : 0        : , "sv"           :
ai_spread_cone_focus_time                : 0        : , "sv"           :
ai_spread_defocused_cone_multiplier      : 3        : , "sv"           :
ai_spread_pattern_focus_time             : 0        : , "sv"           :
ai_strong_optimizations                  : 0        : , "sv"           :
ai_strong_optimizations_no_checkstand    : 0        : , "sv"           :
ai_task_pre_script                       : 0        : , "sv"           :
ai_test_moveprobe_ignoresmall            : 0        : , "sv"           :
ai_think_limit_label                     : 0        : , "a", "sv"      :
ai_use_clipped_paths                     : 1        : , "sv"           :
ai_use_efficiency                        : 1        : , "sv"           :
ai_use_frame_think_limits                : 1        : , "sv"           :
ai_use_think_optimizations               : 1        : , "sv"           :
ai_use_visibility_cache                  : 1        : , "sv"           :
ai_vehicle_avoidance                     : 1        : , "sv", "cheat"  :
air_density                              : cmd      :                  : Changes the density of air for drag computations.
alias                                    : cmd      :                  : Alias a command.
ammo_338mag_max                          : 30       : , "sv", "rep"    :
ammo_357sig_max                          : 52       : , "sv", "rep"    :
ammo_45acp_max                           : 100      : , "sv", "rep"    :
ammo_50AE_max                            : 35       : , "sv", "rep"    :
ammo_556mm_box_max                       : 200      : , "sv", "rep"    :
ammo_556mm_max                           : 90       : , "sv", "rep"    :
ammo_57mm_max                            : 100      : , "sv", "rep"    :
ammo_762mm_max                           : 90       : , "sv", "rep"    :
ammo_9mm_max                             : 120      : , "sv", "rep"    :
ammo_buckshot_max                        : 32       : , "sv", "rep"    :
ammo_flashbang_max                       : 2        : , "sv", "rep"    :
ammo_hegrenade_max                       : 1        : , "sv", "rep"    :
ammo_smokegrenade_max                    : 1        : , "sv", "rep"    :
anim_3wayblend                           : 1        : , "sv", "rep"    : Toggle the 3-way animation blending code.
askconnect_accept                        : cmd      :                  : Accept a redirect request by the server.
async_allow_held_files                   : 1        :                  : Allow AsyncBegin/EndRead()
async_mode                               : 0        :                  : Set the async filesystem mode (0 = async, 1 = synchronous)
async_resume                             : cmd      :                  :
async_serialize                          : 0        :                  : Force async reads to serialize for profiling
async_simulate_delay                     : 0        :                  : Simulate a delay of up to a set msec per file operation
async_suspend                            : cmd      :                  :
audit_save_in_memory                     : cmd      :                  : Audit the memory usage and files in the save-to-memory system
autoaim_max_deflect                      : 0        : , "sv"           :
autoaim_max_dist                         : 2160     : , "sv"           :
autobuy                                  : cmd      :                  : Attempt to purchase items with the order listed in cl_autobuy
autosave                                 : cmd      :                  : Autosave
autosavedangerous                        : cmd      :                  : AutoSaveDangerous
autosavedangerousissafe                  : cmd      :                  :
banid                                    : cmd      :                  : Add a user ID to the ban list.
banip                                    : cmd      :                  : Add an IP address to the ban list.
bench_end                                : cmd      :                  : Ends gathering of info.
bench_start                              : cmd      :                  : Starts gathering of info. Arguments: filename to write results into
bench_upload                             : cmd      :                  : Uploads most recent benchmark stats to the Valve servers.
benchframe                               : cmd      :                  : Takes a snapshot of a particular frame in a time demo.
bind                                     : cmd      :                  : Bind a key.
bind_mac                                 : cmd      :                  : Bind this key but only on Mac, not win32
BindToggle                               : cmd      :                  : Performs a bind <key> 'increment var <cvar> 0 1 1'
bloodspray                               : cmd      :                  : blood
bot_add                                  : cmd      :                  : bot_add <t|ct> <type> <difficulty> <name> - Adds a bot matching the given criteria.
bot_add_ct                               : cmd      :                  : bot_add_ct <type> <difficulty> <name> - Adds a Counter-Terrorist bot matching the given criteria.
bot_add_t                                : cmd      :                  : bot_add_t <type> <difficulty> <name> - Adds a terrorist bot matching the given criteria.
bot_all_weapons                          : cmd      :                  : Allows the bots to use all weapons
bot_allow_grenades                       : 1        : , "sv", "rep"    : If nonzero, bots may use grenades.
bot_allow_machine_guns                   : 1        : , "sv", "rep"    : If nonzero, bots may use the machine gun.
bot_allow_pistols                        : 1        : , "sv", "rep"    : If nonzero, bots may use pistols.
bot_allow_rifles                         : 1        : , "sv", "rep"    : If nonzero, bots may use rifles.
bot_allow_rogues                         : 1        : , "sv", "rep"    : If nonzero, bots may occasionally go 'rogue'. Rogue bots do not obey radio commands, nor pursue scenario goals.
bot_allow_shotguns                       : 1        : , "sv", "rep"    : If nonzero, bots may use shotguns.
bot_allow_snipers                        : 1        : , "sv", "rep"    : If nonzero, bots may use sniper rifles.
bot_allow_sub_machine_guns               : 1        : , "sv", "rep"    : If nonzero, bots may use sub-machine guns.
bot_auto_follow                          : 0        : , "sv", "rep"    : If nonzero, bots with high co-op may automatically follow a nearby human player.
bot_auto_vacate                          : 1        : , "sv", "rep"    : If nonzero, bots will automatically leave to make room for human players.
bot_chatter                              : 0        : , "sv", "rep"    : Control how bots talk. Allowed values: 'off', 'radio', 'minimal', or 'normal'.
bot_crouch                               : 0        : , "sv", "cheat"  :
bot_debug                                : 0        : , "sv", "cheat", "rep" : For internal testing purposes.
bot_debug_target                         : 0        : , "sv", "cheat", "rep" : For internal testing purposes.
bot_defer_to_human                       : 0        : , "sv", "rep"    : If nonzero and there is a human on the team, the bots will not do the scenario tasks.
bot_difficulty                           : 1        : , "sv", "rep"    : Defines the skill of bots joining the game.  Values are: 0=easy, 1=normal, 2=hard, 3=expert.
bot_dont_shoot                           : 0        : , "sv", "cheat", "rep" : If nonzero, bots will not fire weapons (for debugging).
bot_eco_limit                            : 2000     : , "sv", "rep"    : If nonzero, bots will not buy if their money falls below this amount.
bot_flipout                              : 0        : , "sv", "cheat", "rep" : If nonzero, bots use no CPU for AI. Instead, they run around randomly.
bot_freeze                               : 0        : , "sv", "cheat"  :
bot_goto_mark                            : cmd      :                  : Sends a bot to the selected nav area (useful for testing navigation meshes)
bot_join_after_player                    : 1        : , "sv", "rep"    : If nonzero, bots wait until a player joins before entering the game.
bot_join_delay                           : 0        : , "sv"           : Prevents bots from joining the server for this many seconds after a map change.
bot_join_team                            : 0        : , "sv", "rep"    : Determines the team bots will join into. Allowed values: 'any', 'T', or 'CT'.
bot_kick                                 : cmd      :                  : bot_kick <all> <t|ct> <type> <difficulty> <name> - Kicks a specific bot, or all bots, matching the given criteria.
bot_kill                                 : cmd      :                  : bot_kill <all> <t|ct> <type> <difficulty> <name> - Kills a specific bot, or all bots, matching the given criteria.
bot_knives_only                          : cmd      :                  : Restricts the bots to only using knives
bot_loadout                              : 0        : , "sv", "cheat"  : bots are given these items at round start
bot_mimic                                : 0        : , "sv"           : Bot uses usercmd of player by index.
bot_mimic_yaw_offset                     : 180      : , "sv", "cheat"  :
bot_pistols_only                         : cmd      :                  : Restricts the bots to only using pistols
bot_prefix                               : 0        : , "sv", "rep"    : This string is prefixed to the name of all bots that join the game. <difficulty> will be replaced with the bot's difficulty. <weaponclass> will be replaced with the bot's desired weapon class. <skill> will be replaced with a 0-100 representation of the bot's skill.
bot_profile_db                           : 0        : , "sv", "rep"    : The filename from which bot profiles will be read.
bot_quota                                : 0        : , "sv", "nf", "rep" : Determines the total number of bots in the game.
bot_quota_mode                           : 0        : , "sv", "rep"    : Determines the type of quota. Allowed values: 'normal', 'fill', and 'match'. If 'fill', the server will adjust bots to keep N players in the game, where N is bot_quota. If 'match', the server will maintain a 1:N ratio of humans to bots, where N is bot_quota.
bot_randombuy                            : 0        : , "sv", "cheat"  : should bots ignore their prefered weapons and just buy weapons at random?
bot_show_battlefront                     : 0        : , "sv", "cheat"  : Show areas where rushing players will initially meet.
bot_show_nav                             : 0        : , "sv", "cheat", "rep" : For internal testing purposes.
bot_show_occupy_time                     : 0        : , "sv", "cheat"  : Show when each nav area can first be reached by each team.
bot_snipers_only                         : cmd      :                  : Restricts the bots to only using sniper rifles
bot_stop                                 : 0        : , "sv", "cheat", "rep" : If nonzero, immediately stops all bot processing.
bot_traceview                            : 0        : , "sv", "cheat", "rep" : For internal testing purposes.
bot_walk                                 : 0        : , "sv", "rep"    : If nonzero, bots can only walk, not run.
bot_zombie                               : 0        : , "sv", "cheat", "rep" : If nonzero, bots will stay in idle mode and not attack.
box                                      : cmd      :                  : Draw a debug box.
breakable_disable_gib_limit              : 0        : , "sv"           :
breakable_multiplayer                    : 1        : , "sv"           :
buddha                                   : cmd      :                  : Toggle.  Player takes damage but won't die. (Shows red cross when health is zero)
budget_averages_window                   : 30       : , "a"            : number of frames to look at when figuring out average frametimes
budget_background_alpha                  : 128      : , "a"            : how translucent the budget panel is
budget_bargraph_background_alpha         : 128      : , "a"            : how translucent the budget panel is
budget_bargraph_range_ms                 : 16       : , "a"            : budget bargraph range in milliseconds
budget_history_numsamplesvisible         : 100      : , "a"            : number of samples to draw in the budget history window.  The lower the better as far as rendering overhead of the budget panel
budget_history_range_ms                  : 66       : , "a"            : budget history range in milliseconds
budget_panel_bottom_of_history_fraction  : 0        : , "a"            : number between 0 and 1
budget_panel_height                      : 384      : , "a"            : height in pixels of the budget panel
budget_panel_width                       : 512      : , "a"            : width in pixels of the budget panel
budget_panel_x                           : 0        : , "a"            : number of pixels from the left side of the game screen to draw the budget panel
budget_panel_y                           : 50       : , "a"            : number of pixels from the top side of the game screen to draw the budget panel
budget_peaks_window                      : 30       : , "a"            : number of frames to look at when figuring out peak frametimes
budget_show_averages                     : 0        : , "a"            : enable/disable averages in the budget panel
budget_show_history                      : 1        : , "a"            : turn history graph off and on. . good to turn off on low end
budget_show_peaks                        : 1        : , "a"            : enable/disable peaks in the budget panel
budget_toggle_group                      : cmd      :                  : Turn a budget group on/off
bug                                      : cmd      :                  : Show/hide the bug reporting UI.
bug_swap                                 : cmd      :                  : Automatically swaps the current weapon for the bug bait and back again.
bugreporter_includebsp                   : 1        :                  : Include .bsp for internal bug submissions.
bugreporter_uploadasync                  : 0        : , "a"            : Upload attachments asynchronously
buildcubemaps                            : cmd      :                  : Rebuild cubemaps.
building_cubemaps                        : 0        :                  :
cache_print                              : cmd      :                  : cache_print [section] Print out contents of cache memory.
cache_print_lru                          : cmd      :                  : cache_print_lru [section] Print out contents of cache memory.
cache_print_summary                      : cmd      :                  : cache_print_summary [section] Print out a summary contents of cache memory.
callvote                                 : cmd      :                  : Start a vote on an issue.
cast_hull                                : cmd      :                  : Tests hull collision detection
cast_ray                                 : cmd      :                  : Tests collision detection
ch_createairboat                         : cmd      :                  : Spawn airboat in front of the player.
ch_createjeep                            : cmd      :                  : Spawn jeep in front of the player.
changelevel                              : cmd      :                  : Change server to the specified map
changelevel2                             : cmd      :                  : Transition to the specified map in single player
changelevel_next                         : cmd      :                  : Immediately changes to the next map in the map rotation for the server.
cl_allowdownload                         : 1        : , "a"            : Client downloads customization files
cl_allowupload                           : 1        : , "a"            : Client uploads customization files
cl_clock_correction                      : 1        : , "cheat"        : Enable/disable clock correction on the client.
cl_clock_correction_adjustment_max_amount : 200      : , "cheat"        : Sets the maximum number of milliseconds per second it is allowed to correct the client clock. It will only correct this amount if the difference between the client and server clock is equal to or larger than cl_clock_correction_adjustment_max_offset.
cl_clock_correction_adjustment_max_offset : 90       : , "cheat"        : As the clock offset goes from cl_clock_correction_adjustment_min_offset to this value (in milliseconds), it moves towards applying cl_clock_correction_adjustment_max_amount of adjustment. That way, the response is small when the offset is small.
cl_clock_correction_adjustment_min_offset : 10       : , "cheat"        : If the clock offset is less than this amount (in milliseconds), then no clock correction is applied.
cl_clock_correction_force_server_tick    : 999      : , "cheat"        : Force clock correction to match the server tick + this offset (-999 disables it).
cl_clock_showdebuginfo                   : 0        : , "cheat"        : Show debugging info about the clock drift.
cl_clockdrift_max_ms                     : 150      : , "cheat"        : Maximum number of milliseconds the clock is allowed to drift before the client snaps its clock to the server's.
cl_clockdrift_max_ms_threadmode          : 0        : , "cheat"        : Maximum number of milliseconds the clock is allowed to drift before the client snaps its clock to the server's.
cl_cmdrate                               : 30       : , "a", "user"    : Max number of command packets sent to server per second
cl_debug_player_perf                     : 0        :                  :
cl_downloadfilter                        : 0        : , "a"            : Determines which files can be downloaded from the server (all, none, nosounds, mapsonly)
cl_entityreport                          : 0        : , "cheat"        : For debugging, draw entity states to console
cl_entityreport_sorted                   : 0        : , "cheat"        : For debugging, draw entity states to console in sorted order. [0 = disabled, 1 = average, 2 = current, 3 = peak
cl_flushentitypacket                     : 0        : , "cheat"        : For debugging. Force the engine to flush an entity packet.
cl_forcepreload                          : 0        : , "a"            : Whether we should force preloading.
cl_fullupdate                            : cmd      :                  : Forces the server to send a full update packet
cl_ignorepackets                         : 0        : , "cheat"        : Force client to ignore packets (for debugging).
cl_language                              : 0        : , "user"         : Language (from HKCU\Software\Valve\Steam\Language)
cl_localnetworkbackdoor                  : 1        :                  : Enable network optimizations for single player games.
cl_logofile                              : 0        : , "a"            : Spraypoint logo decal.
cl_playback_screenshots                  : 0        :                  : Allows the client to playback screenshot and jpeg commands in demos.
cl_precacheinfo                          : cmd      :                  : Show precache info (client).
cl_resend                                : 6        :                  : Delay in seconds before the client will resend the 'connect' attempt
cl_screenshotname                        : 0        :                  : Custom Screenshot name
cl_show_connectionless_packet_warnings   : 0        :                  : Show console messages about ignored connectionless packets on the client.
cl_showdemooverlay                       : 0        :                  : How often to flash demo recording/playback overlay (0 - disable overlay, -1 - show always)
cl_showents                              : cmd      :                  : Dump entity list to console.
cl_showevents                            : 0        : , "cheat"        : Print event firing info in the console
cl_showpluginmessages                    : 0        : , "a"            : Allow plugins to display messages to you
cl_soundfile                             : 0        : , "a"            : Jingle sound file.
cl_timeout                               : 30       : , "a"            : After this many seconds without receiving a packet from the server, the client will disconnect itself
cl_updaterate                            : 20       : , "a", "user"    : Number of packets per second of updates you are requesting from the server
cl_view                                  : cmd      :                  : Set the view entity index.
cl_voice_filter                          : 0        :                  : Filter voice by name substring
clear                                    : cmd      :                  : Clear all console output.
clear_debug_overlays                     : cmd      :                  : clears debug overlays
clientport                               : 27005    :                  : Host game client port
closecaption                             : 0        : , "a", "user"    : Enable close captioning.
cmd                                      : cmd      :                  : Forward command to server.
collision_shake_amp                      : 0        : , "sv"           :
collision_shake_freq                     : 0        : , "sv"           :
collision_shake_time                     : 0        : , "sv"           :
collision_test                           : cmd      :                  : Tests collision system
colorcorrectionui                        : cmd      :                  : Show/hide the color correction tools UI.
commentary                               : 0        : , "sv"           : Desired commentary mode state.
commentary_available                     : 0        : , "sv"           : Automatically set by the game when a commentary file is available for the current map.
commentary_cvarsnotchanging              : cmd      :                  :
commentary_finishnode                    : cmd      :                  :
con_drawnotify                           : 1        :                  : Disables drawing of notification area (for taking screenshots).
con_enable                               : 0        : , "a"            : Allows the console to be activated.
con_filter_enable                        : 0        :                  : Filters console output based on the setting of con_filter_text. 1 filters completely, 2 displays filtered text brighter than other text.
con_filter_text                          : 0        :                  : Text with which to filter console spew. Set con_filter_enable 1 or 2 to activate.
con_filter_text_out                      : 0        :                  : Text with which to filter OUT of console spew. Set con_filter_enable 1 or 2 to activate.
con_logfile                              : 0        :                  : Console output gets written to this file
con_notifytime                           : 8        :                  : How long to display recent console text to the upper part of the game window
con_nprint_bgalpha                       : 50       :                  : Con_NPrint background alpha.
con_nprint_bgborder                      : 5        :                  : Con_NPrint border size.
con_timestamp                            : 0        :                  : Prefix console.log entries with timestamps
con_trace                                : 0        :                  : Print console text to low level printout.
connect                                  : cmd      :                  : Connect to specified server.
contimes                                 : 8        :                  : Number of console lines to overlay for debugging.
coop                                     : 0        : , "nf"           : Cooperative play.
cpu_frequency_monitoring                 : 0        :                  : Set CPU frequency monitoring interval in seconds. Zero means disabled.
create_flashlight                        : cmd      :                  :
CreatePredictionError                    : cmd      :                  : Create a prediction error
creditsdone                              : cmd      :                  :
cs_make_vip                              : cmd      :                  : Marks a player as the VIP
cs_ShowStateTransitions                  : -2       : , "sv", "cheat"  : cs_ShowStateTransitions <ent index or -1 for all>. Show player state transitions.
cvarlist                                 : cmd      :                  : Show the list of convars/concommands.
datacachesize                            : 256      :                  : Size in MB.
dbghist_addline                          : cmd      :                  : Add a line to the debug history. Format: <category id> <line>
dbghist_dump                             : cmd      :                  : Dump the debug history to the console. Format: <category id>     Categories:      0: Entity I/O      1: AI Decisions      2: Scene Print      3: Alyx Blind      4: Log of damage done to player
deathmatch                               : 1        : , "nf"           : Running a deathmatch server.
debug_materialmodifycontrol              : 0        : , "sv"           :
debug_physimpact                         : 0        : , "sv"           :
debug_touchlinks                         : 0        : , "sv"           : Spew touch link activity
debugsystemui                            : cmd      :                  : Show/hide the debug system UI.
decalfrequency                           : 10       : , "sv", "nf"     :
demo_avellimit                           : 2000     :                  : Angular velocity limit before eyes considered snapped for demo playback.
demo_debug                               : 0        :                  : Demo debug info.
demo_fastforwardfinalspeed               : 20       :                  : Go this fast when starting to hold FF button.
demo_fastforwardramptime                 : 5        :                  : How many seconds it takes to get to full FF speed.
demo_fastforwardstartspeed               : 2        :                  : Go this fast when starting to hold FF button.
demo_gototick                            : cmd      :                  : Skips to a tick in demo.
demo_interplimit                         : 4000     :                  : How much origin velocity before it's considered to have 'teleported' causing interpolation to reset.
demo_interpolateview                     : 1        :                  : Do view interpolation during dem playback.
demo_legacy_rollback                     : 1        :                  : Use legacy view interpolation rollback amount in demo playback.
demo_pause                               : cmd      :                  : Pauses demo playback.
demo_pauseatservertick                   : 0        :                  : Pauses demo playback at server tick
demo_quitafterplayback                   : 0        :                  : Quits game after demo playback.
demo_recordcommands                      : 1        : , "cheat"        : Record commands typed at console into .dem files.
demo_resume                              : cmd      :                  : Resumes demo playback.
demo_setendtick                          : cmd      :                  : Sets end demo playback tick. Set to 0 to disable.
demo_timescale                           : cmd      :                  : Sets demo replay speed.
demo_togglepause                         : cmd      :                  : Toggles demo playback.
demolist                                 : cmd      :                  : Print demo sequence list.
demos                                    : cmd      :                  : Demo demo file sequence.
demoui                                   : cmd      :                  : Show/hide the demo player UI.
demoui2                                  : cmd      :                  : Show/hide the advanced demo player UI (demoui2).
+demoui2                                 : cmd      :                  : Bring the advanced demo player UI (demoui2) to foreground.
-demoui2                                 : cmd      :                  : Send the advanced demo player UI (demoui2) to background.
developer                                : 0        :                  : Set developer message level
devshots_nextmap                         : cmd      :                  : Used by the devshots system to go to the next map in the devshots maplist.
devshots_screenshot                      : cmd      :                  : Used by the -makedevshots system to take a screenshot. For taking your own screenshots, use the 'screenshot' command instead.
differences                              : cmd      :                  : Show all convars which are not at their default values.
disconnect                               : cmd      :                  : Disconnect game from server.
disp_dynamic                             : 0        :                  :
dispcoll_drawplane                       : 0        : , "sv"           :
displaysoundlist                         : 0        : , "sv"           :
download_debug                           : 0        : , "norecord"     :
drawcross                                : cmd      :                  : Draws a cross at the given location  Arguments: x y z
drawline                                 : cmd      :                  : Draws line between two 3D Points.  Green if no collision  Red is collides with something  Arguments: x1 y1 z1 x2 y2 z2
dsp_automatic                            : 0        : , "demo"         :
dsp_db_min                               : 80       : , "demo"         :
dsp_db_mixdrop                           : 0        : , "demo"         :
dsp_dist_max                             : 1440     : , "cheat", "demo" :
dsp_dist_min                             : 0        : , "cheat", "demo" :
dsp_enhance_stereo                       : 0        : , "a"            :
dsp_facingaway                           : 0        : , "demo"         :
dsp_mix_max                              : 0        : , "demo"         :
dsp_mix_min                              : 0        : , "demo"         :
dsp_off                                  : 0        : , "cheat"        :
dsp_player                               : 0        : , "demo", "server_can_execute" :
dsp_reload                               : cmd      :                  :
dsp_room                                 : 0        : , "demo"         :
dsp_slow_cpu                             : 0        : , "a", "demo"    :
dsp_spatial                              : 40       : , "demo"         :
dsp_speaker                              : 50       : , "demo"         :
dsp_vol_2ch                              : 1        : , "demo"         :
dsp_vol_4ch                              : 0        : , "demo"         :
dsp_vol_5ch                              : 0        : , "demo"         :
dsp_volume                               : 1        : , "a", "demo"    :
dsp_water                                : 14       : , "demo"         :
dt_ShowPartialChangeEnts                 : 0        :                  : (SP only) - show entities that were copied using small optimized lists (FL_EDICT_PARTIAL_CHANGE).
dt_UsePartialChangeEnts                  : 1        :                  : (SP only) - enable FL_EDICT_PARTIAL_CHANGE optimization.
dti_flush                                : cmd      :                  : Write out the datatable instrumentation files (you must run with -dti for this to work).
dtwarning                                : 0        :                  : Print data table warnings?
dtwatchclass                             : 0        :                  : Watch all fields encoded with this table.
dtwatchent                               : -1       :                  : Watch this entities data table encoding.
dtwatchvar                               : 0        :                  : Watch the named variable.
dump_entity_sizes                        : cmd      :                  : Print sizeof(entclass)
dump_globals                             : cmd      :                  : Dump all global entities/states
dump_panels                              : cmd      :                  : Dump Panel Tree
dump_x360_cfg                            : cmd      :                  : Dump X360 config files to disk
dump_x360_saves                          : cmd      :                  : Dump X360 save games to disk
dumpentityfactories                      : cmd      :                  : Lists all entity factory names.
dumpeventqueue                           : cmd      :                  : Dump the contents of the Entity I/O event queue to the console.
dumpgamestringtable                      : cmd      :                  : Dump the contents of the game string table to the console.
dumplongticks                            : cmd      :                  : Enables generating minidumps on long ticks.
dumpsavedir                              : cmd      :                  : List the contents of the save directory in memory
dumpstringtables                         : cmd      :                  : Print string tables to console.
echo                                     : cmd      :                  : Echo text to console.
enable_debug_overlays                    : 1        : , "sv", "cheat"  : Enable rendering of debug overlays
endmovie                                 : cmd      :                  : Stop recording movie frames.
endround                                 : cmd      :                  : End the current round.
engine_no_focus_sleep                    : 50       : , "a"            :
ent_absbox                               : cmd      :                  : Displays the total bounding box for the given entity(s) in green.  Some entites will also display entity specific overlays.  Arguments:    {entity_name} / {class_name} / no argument picks what player is looking at
ent_attachments                          : cmd      :                  : Displays the attachment points on an entity.  Arguments:    {entity_name} / {class_name} / no argument picks what player is looking at
ent_autoaim                              : cmd      :                  : Displays the entity's autoaim radius.  Arguments:    {entity_name} / {class_name} / no argument picks what player is looking at
ent_bbox                                 : cmd      :                  : Displays the movement bounding box for the given entity(ies) in orange.  Some entites will also display entity specific overlays.  Arguments:    {entity_name} / {class_name} / no argument picks what player is looking at
ent_cancelpendingentfires                : cmd      :                  : Cancels all ent_fire created outputs that are currently waiting for their delay to expire.
ent_create                               : cmd      :                  : Creates an entity of the given type where the player is looking.  Additional parameters can be passed in in the form: ent_create <entity name> <param 1 name> <param 1> <param 2 name> <param 2>...<param N name> <param N>
ent_debugkeys                            : 0        : , "sv"           :
ent_dump                                 : cmd      :                  : Usage:    ent_dump <entity name>
ent_fire                                 : cmd      :                  : Usage:    ent_fire <target> [action] [value] [delay]
ent_info                                 : cmd      :                  : Usage:    ent_info <class name>
ent_keyvalue                             : cmd      :                  : Applies the comma delimited key=value pairs to the entity with the given Hammer ID.  Format: ent_keyvalue <entity id> <key1> <value1> <key2> <value2> ... <keyN> <valueN>
ent_messages                             : cmd      :                  : Toggles input/output message display for the selected entity(ies).  The name of the entity will be displayed as well as any messages that it sends or receives.  Arguments:    {entity_name} / {class_name} / no argument picks what player is looking at
ent_messages_draw                        : 0        : , "sv", "cheat"  : Visualizes all entity input/output activity.
ent_name                                 : cmd      :                  :
ent_orient                               : cmd      :                  : Orient the specified entity to match the player's angles. By default, only orients target entity's YAW. Use the 'allangles' option to orient on all axis.  Format: ent_orient <entity name> <optional: allangles>
ent_pause                                : cmd      :                  : Toggles pausing of input/output message processing for entities.  When turned on processing of all message will stop.  Any messages displayed with 'ent_messages' will stop fading and be displayed indefinitely. To step through the messages one by one use 'ent_step'.
ent_pivot                                : cmd      :                  : Displays the pivot for the given entity(ies).  (y=up=green, z=forward=blue, x=left=red).   Arguments:    {entity_name} / {class_name} / no argument picks what player is looking at
ent_rbox                                 : cmd      :                  : Displays the total bounding box for the given entity(s) in green.  Some entites will also display entity specific overlays.  Arguments:    {entity_name} / {class_name} / no argument picks what player is looking at
ent_remove                               : cmd      :                  : Removes the given entity(s)  Arguments:    {entity_name} / {class_name} / no argument picks what player is looking at
ent_remove_all                           : cmd      :                  : Removes all entities of the specified type  Arguments:    {entity_name} / {class_name}
ent_rotate                               : cmd      :                  : Rotates an entity by a specified # of degrees
ent_setname                              : cmd      :                  : Sets the targetname of the given entity(s)  Arguments:    {new entity name} {entity_name} / {class_name} / no argument picks what player is looking at
ent_show_response_criteria               : cmd      :                  : Print, to the console, an entity's current criteria set used to select responses.  Arguments:    {entity_name} / {class_name} / no argument picks what player is looking at
ent_step                                 : cmd      :                  : When 'ent_pause' is set this will step through one waiting input / output message at a time.
ent_teleport                             : cmd      :                  : Teleport the specified entity to where the player is looking.  Format: ent_teleport <entity name>
ent_text                                 : cmd      :                  : Displays text debugging information about the given entity(ies) on top of the entity (See Overlay Text)  Arguments:    {entity_name} / {class_name} / no argument picks what player is looking at
ent_viewoffset                           : cmd      :                  : Displays the eye position for the given entity(ies) in red.  Arguments:    {entity_name} / {class_name} / no argument picks what player is looking at
envmap                                   : cmd      :                  :
escape                                   : cmd      :                  : Escape key pressed.
exec                                     : cmd      :                  : Execute script file.
exit                                     : cmd      :                  : Exit the engine.
explode                                  : cmd      :                  : Kills the player with explosive damage
explodevector                            : cmd      :                  : Kills a player applying an explosive force. Usage: explodevector <player> <x value> <y value> <z value>
fadein                                   : cmd      :                  : fadein {time r g b}: Fades the screen in from black or from the specified color over the given number of seconds.
fadeout                                  : cmd      :                  : fadeout {time r g b}: Fades the screen to black or to the specified color over the given number of seconds.
fast_fogvolume                           : 0        :                  :
filesystem_buffer_size                   : 0        :                  : Size of per file buffers. 0 for none
filesystem_max_stdio_read                : 16       :                  :
filesystem_native                        : 1        :                  : Use native FS or STDIO
filesystem_report_buffered_io            : 0        :                  :
filesystem_unbuffered_io                 : 1        :                  :
filesystem_use_overlapped_io             : 1        :                  :
find                                     : cmd      :                  : Find concommands with the specified string in their name/help text.
find_ent                                 : cmd      :                  : Find and list all entities with classnames or targetnames that contain the specified substring. Format: find_ent <substring>
find_ent_index                           : cmd      :                  : Display data for entity matching specified index. Format: find_ent_index <index>
findflags                                : cmd      :                  : Find concommands by flags.
fire_absorbrate                          : 3        : , "sv"           :
fire_dmgbase                             : 1        : , "sv"           :
fire_dmginterval                         : 1        : , "sv"           :
fire_dmgscale                            : 0        : , "sv"           :
fire_extabsorb                           : 5        : , "sv"           :
fire_extscale                            : 12       : , "sv"           :
fire_growthrate                          : 1        : , "sv"           :
fire_heatscale                           : 1        : , "sv"           :
fire_incomingheatscale                   : 0        : , "sv"           :
fire_maxabsorb                           : 50       : , "sv"           :
firetarget                               : cmd      :                  :
fish_dormant                             : 0        : , "sv", "cheat", "rep" : Turns off interactive fish behavior. Fish become immobile and unresponsive.
flex_expression                          : 0        : , "sv"           :
flex_looktime                            : 5        : , "sv"           :
flex_maxawaytime                         : 1        : , "sv"           :
flex_maxplayertime                       : 7        : , "sv"           :
flex_minawaytime                         : 0        : , "sv"           :
flex_minplayertime                       : 5        : , "sv"           :
flex_talk                                : 0        : , "sv"           :
flush                                    : cmd      :                  : Flush unlocked cache memory.
flush_locked                             : cmd      :                  : Flush unlocked and locked cache memory.
fog_enable_water_fog                     : 1        : , "cheat"        :
fogui                                    : cmd      :                  : Show/hide fog control UI.
fov                                      : cmd      :                  : Change players FOV
fps_max                                  : 300      :                  : Frame rate limiter, cannot be set while connected to a server.
free_pass_peek_debug                     : 0        : , "sv"           :
fs_monitor_read_from_pack                : 0        :                  : 0:Off, 1:Any, 2:Sync only
fs_printopenfiles                        : cmd      :                  : Show all files currently opened by the engine.
fs_report_sync_opens                     : 0        :                  : 0:Off, 1:Always, 2:Not during load
fs_warning_level                         : cmd      :                  : Set the filesystem warning level.
fs_warning_mode                          : 0        :                  : 0:Off, 1:Warn main thread, 2:Warn other threads
func_break_max_pieces                    : 15       : , "a", "sv", "rep" :
func_break_reduction_factor              : 0        : , "sv"           :
func_breakdmg_bullet                     : 0        : , "sv"           :
func_breakdmg_club                       : 1        : , "sv"           :
func_breakdmg_explosive                  : 1        : , "sv"           :
g_debug_angularsensor                    : 0        : , "sv", "cheat"  :
g_debug_constraint_sounds                : 0        : , "sv", "cheat"  : Enable debug printing about constraint sounds.
g_debug_doors                            : 0        : , "sv"           :
g_debug_npc_vehicle_roles                : 0        : , "sv"           :
g_debug_ragdoll_removal                  : 0        : , "sv", "cheat", "rep" :
g_debug_trackpather                      : 0        : , "sv", "cheat"  :
g_debug_transitions                      : 0        : , "sv"           : Set to 1 and restart the map to be warned if the map has no trigger_transition volumes. Set to 2 to see a dump of all entities & associated results during a transition.
g_debug_vehiclebase                      : 0        : , "sv", "cheat"  :
g_debug_vehicledriver                    : 0        : , "sv", "cheat"  :
g_debug_vehicleexit                      : 0        : , "sv", "cheat"  :
g_debug_vehiclesound                     : 0        : , "sv", "cheat"  :
g_jeepexitspeed                          : 100      : , "sv", "cheat"  :
g_Language                               : 0        : , "sv", "rep"    :
g_ragdoll_important_maxcount             : 2        : , "sv", "rep"    :
g_ragdoll_maxcount                       : 8        : , "sv", "rep"    :
gameui_activate                          : cmd      :                  : Shows the game UI
gameui_allowescape                       : cmd      :                  : Escape key allowed to hide game UI
gameui_allowescapetoshow                 : cmd      :                  : Escape key allowed to show game UI
gameui_hide                              : cmd      :                  : Hides the game UI
gameui_preventescape                     : cmd      :                  : Escape key doesn't hide game UI
gameui_preventescapetoshow               : cmd      :                  : Escape key doesn't show game UI
gameui_xbox                              : 0        :                  :
give                                     : cmd      :                  : Give item to player.  Arguments: <item_name>
givecurrentammo                          : cmd      :                  : Give a supply of ammo for current weapon..
gl_amd_occlusion_workaround              : 1        :                  :
global_set                               : cmd      :                  : global_set <globalname> <state>: Sets the state of the given env_global (0 = OFF, 1 = ON, 2 = DEAD).
god                                      : cmd      :                  : Toggle. Player becomes invulnerable.
groundlist                               : cmd      :                  : Display ground entity list <index>
hammer_update_entity                     : cmd      :                  : Updates the entity's position/angles when in edit mode
hammer_update_safe_entities              : cmd      :                  : Updates entities in the map that can safely be updated (don't have parents or are affected by constraints). Also excludes entities mentioned in any hammer_updateignorelist objects in this map.
heartbeat                                : cmd      :                  : Force heartbeat of master servers
help                                     : cmd      :                  : Find help about a convar/concommand.
hideconsole                              : cmd      :                  : Hide the console.
hl2_episodic                             : 0        : , "sv", "rep"    :
host_flush_threshold                     : 20       :                  : Memory threshold below which the host should flush caches between server instances
host_framerate                           : 0        :                  : Set to lock per-frame time elapse.
host_limitlocal                          : 0        :                  : Apply cl_cmdrate and cl_updaterate to loopback connection
host_map                                 : 0        :                  : Current map name.
host_profile                             : 0        :                  :
host_runofftime                          : cmd      :                  : Run off some time without rendering/updating sounds
host_showcachemiss                       : 0        :                  : Print a debug message when the client or server cache is missed.
host_ShowIPCCallCount                    : 0        :                  : Print # of IPC calls this number of times per second. If set to -1, the # of IPC calls is shown every frame.
host_sleep                               : 0        : , "cheat"        : Force the host to sleep a certain number of milliseconds each frame.
host_speeds                              : 0        :                  : Show general system running times.
host_thread_mode                         : 0        :                  : Run the host in threaded mode, (0 == off, 1 == if multicore, 2 == force)
host_timer_report                        : cmd      :                  : Spew CPU timer jitter for the last 128 frames in microseconds (dedicated only)
host_timer_spin_ms                       : 0        :                  : Use CPU busy-loop for improved timer precision (dedicated only)
host_timescale                           : 1        : , "rep"          : Prescale the clock by this amount.
host_writeconfig                         : cmd      :                  : Store current settings to config.cfg (or specified .cfg file).
hostage_debug                            : 0        : , "sv", "cheat"  : Show hostage AI debug information
hostip                                   : -1062731648.000 :                  : Host game server ip
hostname                                 : 0        :                  : Hostname for server.
hostport                                 : 27015    :                  : Host game server port
hud_jeephint_numentries                  : 10       : , "sv"           :
hurtme                                   : cmd      :                  : Hurts the player.  Arguments: <health to lose>
incrementvar                             : cmd      :                  : Increment specified convar value.
ip                                       : 0        :                  : Overrides IP for multihomed hosts
joy_active                               : -1       :                  : Which of the connected joysticks / gamepads to use (-1 means first found)
joy_axis_deadzone                        : 0        : , "a"            : Dead zone near the zero point to not report movement.
joy_axisbutton_threshold                 : 0        : , "a"            : Analog axis range before a button press is registered.
joy_gamecontroller_config                : 0        : , "a"            : Game controller mapping (passed to SDL with SDL_HINT_GAMECONTROLLERCONFIG), can also be configured in Steam Big Picture mode.
joy_xcontroller_found                    : 0        :                  : Automatically set to 1 if an xcontroller has been detected.
jpeg                                     : cmd      :                  : Take a jpeg screenshot:  jpeg <filename> <quality 1-100>.
jpeg_quality                             : 90       :                  : jpeg screenshot quality.
kdtree_test                              : cmd      :                  : Tests spatial partition for entities queries.
key_findbinding                          : cmd      :                  : Find key bound to specified command string.
key_listboundkeys                        : cmd      :                  : List bound keys with bindings.
key_updatelayout                         : cmd      :                  : Updates game keyboard layout to current windows keyboard setting.
kick                                     : cmd      :                  : Kick a player by name.
kickall                                  : cmd      :                  : Kicks everybody connected with a message.
kickid                                   : cmd      :                  : Kick a player by userid or uniqueid, with a message.
kill                                     : cmd      :                  : Kills the player with generic damage
killserver                               : cmd      :                  : Shutdown the server.
killvector                               : cmd      :                  : Kills a player applying force. Usage: killvector <player> <x value> <y value> <z value>
light_crosshair                          : cmd      :                  : Show texture color at crosshair
lightcache_maxmiss                       : 2        : , "cheat"        :
lightprobe                               : cmd      :                  : Samples the lighting environment. Creates a cubemap and a file indicating the local lighting in a subdirectory called 'materials/lightprobes' .The lightprobe command requires you specify a base file name.
linefile                                 : cmd      :                  : Parses map leak data from .lin file
listdemo                                 : cmd      :                  : List demo file contents.
listid                                   : cmd      :                  : Lists banned users.
listip                                   : cmd      :                  : List IP addresses on the ban list.
listissues                               : cmd      :                  : List all the issues that can be voted on.
listmodels                               : cmd      :                  : List loaded models.
listRecentNPCSpeech                      : cmd      :                  : Displays a list of the last 5 lines of speech from NPCs.
load                                     : cmd      :                  : Load a saved game.
loader_dump_table                        : cmd      :                  :
loader_spew_info                         : 0        :                  : 0:Off, 1:Timing, 2:Completions, 3:Late Completions, 4:Purges, -1:All
loader_spew_info_ex                      : 0        :                  : (internal)
log                                      : cmd      :                  : Enables logging to file, console, and udp < on | off >.
log_verbose_enable                       : 0        : , "sv"           : Set to 1 to enable verbose server log on the server.
log_verbose_interval                     : 3        : , "sv"           : Determines the interval (in seconds) for the verbose server log.
logaddress_add                           : cmd      :                  : Set address and port for remote host <ip:port>.
logaddress_del                           : cmd      :                  : Remove address and port for remote host <ip:port>.
logaddress_delall                        : cmd      :                  : Remove all udp addresses being logged to
logaddress_list                          : cmd      :                  : List all addresses currently being used by logaddress.
lservercfgfile                           : 0        : , "sv"           :
map                                      : cmd      :                  : Start playing on specified map.
map_background                           : cmd      :                  : Runs a map as the background to the main menu.
map_commentary                           : cmd      :                  : Start playing, with commentary, on a specified map.
map_edit                                 : cmd      :                  :
map_noareas                              : 0        :                  : Disable area to area connection testing.
map_setbombradius                        : cmd      :                  : Sets the bomb radius for the map.
map_showbombradius                       : cmd      :                  : Shows bomb radius from the center of each bomb site and planted bomb.
map_showspawnpoints                      : cmd      :                  : Shows player spawn points (red=invalid)
mapcyclefile                             : 0        : , "sv"           : Name of the .txt file used to cycle the maps on multiplayer servers
maps                                     : cmd      :                  : Displays list of maps.
mat_aaquality                            : 0        :                  :
mat_accelerate_adjust_exposure_down      : 3        : , "cheat"        :
mat_antialias                            : 0        :                  :
mat_bufferprimitives                     : 1        :                  :
mat_bumpbasis                            : 0        : , "cheat"        :
mat_bumpmap                              : 1        :                  :
mat_colcorrection_disableentities        : 0        :                  :
mat_color_projection                     : 0        : , "a"            :
mat_colorcorrection                      : 0        :                  :
mat_compressedtextures                   : 1        :                  :
mat_configcurrent                        : cmd      :                  : show the current video control panel config for the material system
mat_crosshair                            : cmd      :                  : Display the name of the material under the crosshair
mat_crosshair_edit                       : cmd      :                  : open the material under the crosshair in the editor defined by mat_crosshair_edit_editor
mat_crosshair_explorer                   : cmd      :                  : open the material under the crosshair in explorer and highlight the vmt file
mat_crosshair_printmaterial              : cmd      :                  : print the material under the crosshair
mat_crosshair_reloadmaterial             : cmd      :                  : reload the material under the crosshair
mat_debugalttab                          : 0        : , "cheat"        :
mat_debugdepth                           : 0        :                  :
mat_debugdepthmode                       : 0        :                  :
mat_debugdepthval                        : 128      :                  :
mat_debugdepthvalmax                     : 256      :                  :
mat_depthbias_decal                      : -262144  : , "cheat"        :
mat_depthbias_normal                     : 0        : , "cheat"        :
mat_depthbias_shadowmap                  : 0        : , "cheat"        :
mat_diffuse                              : 1        : , "cheat"        :
mat_disable_fancy_blending               : 0        :                  :
mat_disable_lightwarp                    : 0        :                  :
mat_drawflat                             : 0        : , "cheat"        :
mat_drawTitleSafe                        : 0        :                  : Enable title safe overlay
mat_dxlevel                              : 0        :                  :
mat_dynamic_tonemapping                  : 1        : , "cheat"        :
mat_edit                                 : cmd      :                  : Bring up the material under the crosshair in the editor
mat_enable_vrmode                        : cmd      :                  : Switches the material system to VR mode (after restart)
mat_envmapsize                           : 128      :                  :
mat_envmaptgasize                        : 32       :                  :
mat_excludetextures                      : 0        : , "cheat"        :
mat_fastnobump                           : 0        : , "cheat"        :
mat_fastspecular                         : 1        :                  : Enable/Disable specularity for visual testing.  Will not reload materials and will not affect perf.
mat_fillrate                             : 0        : , "cheat"        :
mat_filterlightmaps                      : 1        :                  :
mat_filtertextures                       : 1        :                  :
mat_force_tonemap_scale                  : 0        : , "cheat"        :
mat_forceaniso                           : 1        :                  :
mat_forcedynamic                         : 0        : , "cheat"        :
mat_forcehardwaresync                    : 1        :                  :
mat_forcemanagedtextureintohardware      : 1        :                  :
mat_fullbright                           : 0        : , "cheat"        :
mat_hdr_enabled                          : cmd      :                  : Report if HDR is enabled for debugging
mat_hdr_level                            : 2        : , "a"            : Set to 0 for no HDR, 1 for LDR+bloom on HDR maps, and 2 for full HDR on HDR maps.
mat_hdr_manual_tonemap_rate              : 1        :                  :
mat_hdr_tonemapscale                     : 1        : , "cheat"        : The HDR tonemap scale. 1 = Use autoexposure, 0 = eyes fully closed, 16 = eyes wide open.
mat_info                                 : cmd      :                  : Shows material system info
mat_leafvis                              : 0        : , "cheat"        : Draw wireframe of current leaf
mat_levelflush                           : 1        :                  :
mat_lightmap_pfms                        : 0        :                  : Outputs .pfm files containing lightmap data for each lightmap page when a level exits.
mat_loadtextures                         : 1        : , "cheat"        :
mat_luxels                               : 0        : , "cheat"        :
mat_managedtextures                      : 1        : , "a"            : If set, allows Direct3D to manage texture uploading at the cost of extra system memory
mat_max_worldmesh_vertices               : 65536    :                  :
mat_maxframelatency                      : 1        :                  :
mat_measurefillrate                      : 0        : , "cheat"        :
mat_mipmaptextures                       : 1        :                  :
mat_monitorgamma                         : 2        :                  : monitor gamma (typically 2.2 for CRT and 1.7 for LCD)
mat_monitorgamma_tv_enabled              : 0        : , "a"            :
mat_monitorgamma_tv_exp                  : 2        :                  :
mat_monitorgamma_tv_range_max            : 255      :                  :
mat_monitorgamma_tv_range_min            : 16       :                  :
mat_morphstats                           : 0        : , "cheat"        :
mat_motion_blur_enabled                  : 0        :                  :
mat_motion_blur_percent_of_screen_max    : 4        :                  :
mat_norendering                          : 0        : , "cheat"        :
mat_normalmaps                           : 0        : , "cheat"        :
mat_normals                              : 0        : , "cheat"        :
mat_parallaxmap                          : 1        :                  :
mat_phong                                : 1        :                  :
mat_picmip                               : 0        :                  :
mat_powersavingsmode                     : 0        : , "a"            : Power Savings Mode
mat_proxy                                : 0        : , "cheat"        :
mat_queue_mode                           : -1       : , "a"            : The queue/thread mode the material system should use: -1=default, 0=synchronous single thread, 2=queued multithreaded
mat_queue_report                         : 0        : , "a"            : Report thread stalls.  Positive number will filter by stalls >= time in ms.  -1 reports all locks.
mat_reducefillrate                       : 0        :                  :
mat_reduceparticles                      : 0        :                  :
mat_reloadallmaterials                   : cmd      :                  : Reloads all materials
mat_reloadmaterial                       : cmd      :                  : Reloads a single material
mat_reloadtextures                       : cmd      :                  : Reloads all textures
mat_report_queue_status                  : 0        :                  :
mat_reporthwmorphmemory                  : cmd      :                  : Reports the amount of size in bytes taken up by hardware morph textures.
mat_reset_rendertargets                  : cmd      :                  : Resets all the render targets
mat_reversedepth                         : 0        : , "cheat"        :
mat_savechanges                          : cmd      :                  : saves current video configuration to the registry
mat_setvideomode                         : cmd      :                  : sets the width, height, windowed state of the material system
mat_shadowstate                          : 1        :                  :
mat_show_ab_hdr                          : 0        :                  :
mat_show_texture_memory_usage            : 0        : , "cheat", "numeric" : Display the texture memory usage on the HUD.
mat_showenvmapmask                       : 0        :                  :
mat_showlowresimage                      : 0        : , "cheat"        :
mat_showmaterials                        : cmd      :                  : Show materials.
mat_showmaterialsverbose                 : cmd      :                  : Show materials (verbose version).
mat_showmiplevels                        : 0        : , "cheat"        : color-code miplevels 2: normalmaps, 1: everything else
mat_showtextures                         : cmd      :                  : Show used textures.
mat_slopescaledepthbias_decal            : 0        : , "cheat"        :
mat_slopescaledepthbias_normal           : 0        : , "cheat"        :
mat_slopescaledepthbias_shadowmap        : 16       : , "cheat"        :
mat_softwarelighting                     : 0        :                  :
mat_softwareskin                         : 0        : , "cheat"        :
mat_specular                             : 1        :                  : Enable/Disable specularity for perf testing.  Will cause a material reload upon change.
mat_spew_on_texture_size                 : 0        :                  : Print warnings about vtf content that isn't of the expected size
mat_supportflashlight                    : -1       :                  : 0 - do not support flashlight (don't load flashlight shader combos), 1 - flashlight is supported
mat_surfaceid                            : 0        : , "cheat"        :
mat_surfacemat                           : 0        : , "cheat"        :
mat_texture_list                         : 0        : , "cheat"        : For debugging, show a list of used textures per frame
+mat_texture_list                        : cmd      :                  :
-mat_texture_list                        : cmd      :                  :
mat_texture_list_all                     : 0        : , "cheat", "numeric" : If this is nonzero, then the texture list panel will show all currently-loaded textures.
mat_texture_list_content_path            : 0        : , "a"            : The content path to the materialsrc directory. If left unset, it'll assume your content directory is next to the currently running game dir.
mat_texture_list_txlod                   : cmd      :                  : Adjust LOD of the last viewed texture +1 to inc resolution, -1 to dec resolution
mat_texture_list_txlod_sync              : cmd      :                  : 'reset' - resets all run-time changes to LOD overrides, 'save' - saves all changes to material content files
mat_texture_list_view                    : 1        : , "cheat", "numeric" : If this is nonzero, then the texture list panel will render thumbnails of currently-loaded textures.
mat_texture_save_fonts                   : cmd      :                  : Save all font textures
mat_texture_tracking                     : 0        :                  :
mat_tonemap_algorithm                    : 1        : , "cheat"        : 0 = Original Algorithm 1 = New Algorithm
mat_tonemapping_occlusion_use_stencil    : 0        :                  :
mat_trilinear                            : 0        :                  :
mat_use_compressed_hdr_textures          : 1        :                  :
mat_visualize_dof                        : 0        : , "cheat"        :
mat_vrmode_adapter                       : -1       :                  :
mat_vsync                                : 0        :                  : Force sync to vertical retrace
mat_wireframe                            : 0        : , "cheat"        :
matchmakingport                          : 27025    :                  : Host Matchmaking port
maxplayers                               : cmd      :                  : Change the maximum number of players allowed on this server.
mem_compact                              : cmd      :                  :
mem_dump                                 : cmd      :                  : Dump memory stats to text file.
mem_dumpstats                            : 0        :                  : Dump current and max heap usage info to console at end of frame ( set to 2 for continuous output )
mem_eat                                  : cmd      :                  :
mem_force_flush                          : 0        : , "cheat"        : Force cache flush of unlocked resources on every alloc
mem_max_heapsize                         : 256      :                  : Maximum amount of memory to dedicate to engine hunk and datacache (in mb)
mem_max_heapsize_dedicated               : 64       :                  : Maximum amount of memory to dedicate to engine hunk and datacache, for dedicated server (in mb)
mem_min_heapsize                         : 48       :                  : Minimum amount of memory to dedicate to engine hunk and datacache (in mb)
mem_periodicdumps                        : 0        :                  : Write periodic memstats dumps every n seconds.
mem_test                                 : cmd      :                  :
mem_test_each_frame                      : 0        :                  : Run heap check at end of every frame
mem_test_every_n_seconds                 : 0        :                  : Run heap check at a specified interval
mem_vcollide                             : cmd      :                  : Dumps the memory used by vcollides
memory                                   : cmd      :                  : Print memory stats.
memory_diff                              : cmd      :                  : show memory stats relative to snapshot
memory_list                              : cmd      :                  : dump memory list (linux only)
memory_mark                              : cmd      :                  : snapshot current allocation status
memory_status                            : cmd      :                  : show memory stats (linux only)
minisave                                 : cmd      :                  : Saves game (for current level only!)
mission_list                             : cmd      :                  : List all available tactical missions
mission_show                             : cmd      :                  : Show the given mission
mm_max_spectators                        : 4        :                  : Max players allowed on the spectator team
mm_message                               : cmd      :                  : Send a message to all remote clients
mm_minplayers                            : 2        :                  : Number of players required to start an unranked game
mm_select_session                        : cmd      :                  : Select a session
mm_session_info                          : cmd      :                  : Dump session information
mm_stats                                 : cmd      :                  :
mod_forcedata                            : 1        :                  : Forces all model file data into cache on model load.
mod_forcetouchdata                       : 1        :                  : Forces all model file data into cache on model load.
mod_load_anims_async                     : 0        :                  :
mod_load_fakestall                       : 0        :                  : Forces all ANI file loading to stall for specified ms
mod_load_mesh_async                      : 0        :                  :
mod_load_showstall                       : 0        :                  : 1 - show hitches , 2 - show stalls
mod_load_vcollide_async                  : 0        :                  :
mod_lock_mdls_on_load                    : 0        :                  :
mod_test_mesh_not_available              : 0        : , "cheat"        :
mod_test_not_available                   : 0        : , "cheat"        :
mod_test_verts_not_available             : 0        : , "cheat"        :
mod_touchalldata                         : 1        :                  : Touch model data during level startup
mod_trace_load                           : 0        :                  :
model_list                               : cmd      :                  : Dump model list to file
motdfile                                 : 0        : , "sv"           : The MOTD file to load.
motdfile_text                            : 0        : , "sv"           : The text-only MOTD file to use for clients that have disabled HTML MOTDs.
movie_fixwave                            : cmd      :                  : Fixup corrupted .wav file if engine crashed during startmovie/endmovie, etc.
mp_allowNPCs                             : 1        : , "sv", "nf"     :
mp_allowspectators                       : 1        : , "sv", "rep"    : toggles whether the server allows spectator mode or not
mp_autocrosshair                         : 1        : , "sv", "nf"     :
mp_autokick                              : 1        : , "sv", "rep"    : Kick idle/team-killing players
mp_autoteambalance                       : 1        : , "sv", "nf"     :
mp_bonusroundtime                        : 15       : , "sv", "rep"    : Time after round win until round restarts
mp_bonusroundtime_final                  : 15       : , "sv", "rep"    : Time after final round ends until round restarts
mp_buytime                               : 1        : , "sv", "rep"    : How many minutes after round start players can buy items for.
mp_c4timer                               : 45       : , "sv", "nf", "rep" : how long from when the C4 is armed until it blows
mp_chattime                              : 10       : , "sv", "rep"    : amount of time players can chat after the game is over
mp_clan_ready_signal                     : 0        : , "sv"           : Text that team leader from each team must speak for the match to begin
mp_clan_readyrestart                     : 0        : , "sv"           : If non-zero, game will restart once someone from each team gives the ready signal
mp_decals                                : 200      : , "a"            :
mp_defaultteam                           : 0        : , "sv"           :
mp_disable_autokick                      : cmd      :                  : Prevents a userid from being auto-kicked
mp_disable_respawn_times                 : 0        : , "sv", "nf", "rep" :
mp_dump_timers                           : cmd      :                  : Prints round timers to the console for debugging
mp_enableroundwaittime                   : 1        : , "sv", "rep"    : Enable timers to wait between rounds.
mp_fadetoblack                           : 0        : , "sv", "nf", "rep" : fade a player's screen to black when he dies
mp_falldamage                            : 0        : , "sv", "nf"     :
mp_flashlight                            : 0        : , "sv", "nf"     :
mp_footsteps                             : 1        : , "sv", "nf"     :
mp_forceautoteam                         : 0        : , "sv", "nf", "rep" : Automatically assign players to teams when joining.
mp_forcecamera                           : 1        : , "sv", "rep"    : Restricts spectator modes for dead players
mp_forcerespawn                          : 1        : , "sv", "nf"     :
mp_forcerespawnplayers                   : cmd      :                  : Force all players to respawn.
mp_forcewin                              : cmd      :                  : Forces team to win
mp_fraglimit                             : 0        : , "sv", "nf", "rep" : The number of kills at which the map ends
mp_freezetime                            : 6        : , "sv", "nf", "rep" : how many seconds to keep players frozen when the round starts
mp_friendlyfire                          : 0        : , "sv", "nf", "rep" : Allows team members to injure other members of their team
mp_holiday_nogifts                       : 0        : , "sv", "nf"     : Set to 1 to prevent holiday gifts from spawning when players are killed.
mp_hostagepenalty                        : 13       : , "sv", "nf"     : Terrorist are kicked for killing too much hostages
mp_humanteam                             : 0        : , "sv", "rep"    : Restricts human players to a single team {any, CT, T}
mp_ignore_round_win_conditions           : 0        : , "sv", "rep"    : Ignore conditions which would end the current round
mp_limitteams                            : 2        : , "sv", "nf", "rep" : Max # of players 1 team can have over another (0 disables check)
mp_logdetail                             : 0        : , "sv"           : Logs attacks.  Values are: 0=off, 1=enemy, 2=teammate, 3=both)
mp_mapcycle_empty_timeout_seconds        : 0        : , "sv", "rep"    : If nonzero, server will cycle to the next map if it has been empty on the current map for N seconds
mp_match_end_at_timelimit                : 0        : , "sv", "nf"     : Allow the match to end when mp_timelimit hits instead of waiting for the end of the current round.
mp_maxrounds                             : 0        : , "sv", "nf", "rep" : max number of rounds to play before server changes maps
mp_playerid                              : 0        : , "sv", "rep"    : Controls what information player see in the status bar: 0 all names; 1 team names; 2 no names
mp_playerid_delay                        : 0        : , "sv", "rep"    : Number of seconds to delay showing information in the status bar
mp_playerid_hold                         : 0        : , "sv", "rep"    : Number of seconds to keep showing old information in the status bar
mp_respawnwavetime                       : 10       : , "sv", "nf", "rep" : Time between respawn waves.
mp_restartgame                           : 0        : , "sv"           : If non-zero, game will restart in the specified number of seconds
mp_restartgame_immediate                 : 0        : , "sv"           : If non-zero, game will restart immediately
mp_restartround                          : 0        : , "sv"           : If non-zero, the current round will restart in the specified number of seconds
mp_round_restart_delay                   : 5        : , "sv", "rep"    : Number of seconds to delay before restarting a round after a win
mp_roundtime                             : 2        : , "sv", "nf", "rep" : How many minutes each round takes.
mp_scrambleteams                         : cmd      :                  : Scramble the teams and restart the game
mp_scrambleteams_auto                    : 1        : , "sv", "nf"     : Server will automatically scramble the teams if criteria met.  Only works on dedicated servers.
mp_scrambleteams_auto_windifference      : 2        : , "sv", "nf"     : Number of round wins a team must lead by in order to trigger an auto scramble.
mp_show_voice_icons                      : 1        : , "sv", "rep"    : Show overhead player voice icons when players are speaking.
mp_spawnprotectiontime                   : 5        : , "sv", "rep"    : Kick players who team-kill within this many seconds of a round restart.
mp_stalemate_enable                      : 0        : , "sv", "nf"     : Enable/Disable stalemate mode.
mp_stalemate_meleeonly                   : 0        : , "sv", "nf", "rep" : Restrict everyone to melee weapons only while in Sudden Death.
mp_stalemate_timelimit                   : 240      : , "sv", "rep"    : Timelimit (in seconds) of the stalemate round.
mp_startmoney                            : 800      : , "sv", "nf", "rep" : amount of money each player gets when they reset
mp_switchteams                           : cmd      :                  : Switch teams and restart the game
mp_teamlist                              : 0        : , "sv", "nf"     :
mp_teamoverride                          : 1        : , "sv"           :
mp_teamplay                              : 0        : , "sv", "nf"     :
mp_teams_unbalance_limit                 : 1        : , "sv", "rep"    : Teams are unbalanced when one team has this many more players than the other team. (0 disables check)
mp_timelimit                             : 0        : , "sv", "nf", "rep" : game time per map in minutes
mp_tkpunish                              : 0        : , "sv", "rep"    : Will a TK'er be punished in the next round?  {0=no,  1=yes}
mp_tournament                            : 0        : , "sv", "nf", "rep" :
mp_tournament_allow_non_admin_restart    : 1        : , "sv"           : Allow mp_tournament_restart command to be issued by players other than admin.
mp_tournament_restart                    : cmd      :                  : Restart Tournament Mode on the current level.
mp_waitingforplayers_cancel              : 0        : , "sv"           : Set to 1 to end the WaitingForPlayers period.
mp_waitingforplayers_restart             : 0        : , "sv"           : Set to 1 to start or restart the WaitingForPlayers period.
mp_waitingforplayers_time                : 0        : , "sv"           : WaitingForPlayers time length in seconds
mp_weaponstay                            : 0        : , "sv", "nf"     :
mp_winlimit                              : 0        : , "sv", "nf", "rep" : Max score one team can reach before server changes maps
multvar                                  : cmd      :                  : Multiply specified convar value.
name                                     : 0        : , "a", "user", "print", "server_can_execute" : Current user name
namelockid                               : cmd      :                  : Prevent name changes for this userID.
nav_add_to_selected_set                  : cmd      :                  : Add current area to the selected set.
nav_add_to_selected_set_by_id            : cmd      :                  : Add specified area id to the selected set.
nav_analyze                              : cmd      :                  : Re-analyze the current Navigation Mesh and save it to disk.
nav_area_bgcolor                         : 0        : , "sv", "cheat"  : RGBA color to draw as the background color for nav areas while editing.
nav_area_max_size                        : 50       : , "sv", "cheat"  : Max area size created in nav generation
nav_avoid                                : cmd      :                  : Toggles the 'avoid this area when possible' flag used by the AI system.
nav_begin_area                           : cmd      :                  : Defines a corner of a new Area or Ladder. To complete the Area or Ladder, drag the opposite corner to the desired location and issue a 'nav_end_area' command.
nav_begin_deselecting                    : cmd      :                  : Start continuously removing from the selected set.
nav_begin_drag_deselecting               : cmd      :                  : Start dragging a selection area.
nav_begin_drag_selecting                 : cmd      :                  : Start dragging a selection area.
nav_begin_selecting                      : cmd      :                  : Start continuously adding to the selected set.
nav_begin_shift_xy                       : cmd      :                  : Begin shifting the Selected Set.
nav_build_ladder                         : cmd      :                  : Attempts to build a nav ladder on the climbable surface under the cursor.
nav_check_connectivity                   : cmd      :                  : Checks to be sure every (or just the marked) nav area can get to every goal area for the map (hostages or bomb site).
nav_check_file_consistency               : cmd      :                  : Scans the maps directory and reports any missing/out-of-date navigation files.
nav_check_floor                          : cmd      :                  : Updates the blocked/unblocked status for every nav area.
nav_check_stairs                         : cmd      :                  : Update the nav mesh STAIRS attribute
nav_chop_selected                        : cmd      :                  : Chops all selected areas into their component 1x1 areas
nav_clear_attribute                      : cmd      :                  : Remove given nav attribute from all areas in the selected set.
nav_clear_selected_set                   : cmd      :                  : Clear the selected set.
nav_clear_walkable_marks                 : cmd      :                  : Erase any previously placed walkable positions.
nav_compress_id                          : cmd      :                  : Re-orders area and ladder ID's so they are continuous.
nav_connect                              : cmd      :                  : To connect two Areas, mark the first Area, highlight the second Area, then invoke the connect command. Note that this creates a ONE-WAY connection from the first to the second Area. To make a two-way connection, also connect the second area to the first.
nav_coplanar_slope_limit                 : 0        : , "sv", "cheat"  :
nav_coplanar_slope_limit_displacement    : 0        : , "sv", "cheat"  :
nav_corner_adjust_adjacent               : 18       : , "sv", "cheat"  : radius used to raise/lower corners in nearby areas when raising/lowering corners.
nav_corner_lower                         : cmd      :                  : Lower the selected corner of the currently marked Area.
nav_corner_place_on_ground               : cmd      :                  : Places the selected corner of the currently marked Area on the ground.
nav_corner_raise                         : cmd      :                  : Raise the selected corner of the currently marked Area.
nav_corner_select                        : cmd      :                  : Select a corner of the currently marked Area. Use multiple times to access all four corners.
nav_create_area_at_feet                  : 0        : , "sv", "cheat"  : Anchor nav_begin_area Z to editing player's feet
nav_create_place_on_ground               : 0        : , "sv", "cheat"  : If true, nav areas will be placed flush with the ground when created by hand.
nav_crouch                               : cmd      :                  : Toggles the 'must crouch in this area' flag used by the AI system.
nav_debug_blocked                        : 0        : , "sv", "cheat"  :
nav_delete                               : cmd      :                  : Deletes the currently highlighted Area.
nav_delete_marked                        : cmd      :                  : Deletes the currently marked Area (if any).
nav_disconnect                           : cmd      :                  : To disconnect two Areas, mark an Area, highlight a second Area, then invoke the disconnect command. This will remove all connections between the two Areas.
nav_disconnect_outgoing_oneways          : cmd      :                  : For each area in the selected set, disconnect all outgoing one-way connections.
nav_displacement_test                    : 10000    : , "sv", "cheat"  : Checks for nodes embedded in displacements (useful for in-development maps)
nav_dont_hide                            : cmd      :                  : Toggles the 'area is not suitable for hiding spots' flag used by the AI system.
nav_drag_selection_volume_zmax_offset    : 32       : , "sv", "rep"    : The offset of the nav drag volume top from center
nav_drag_selection_volume_zmin_offset    : 32       : , "sv", "rep"    : The offset of the nav drag volume bottom from center
nav_draw_limit                           : 500      : , "sv", "cheat"  : The maximum number of areas to draw in edit mode
nav_dump_selected_set_positions          : cmd      :                  : Write the (x,y,z) coordinates of the centers of all selected nav areas to a file.
nav_edit                                 : 0        : , "sv", "cheat"  : Set to one to interactively edit the Navigation Mesh. Set to zero to leave edit mode.
nav_end_area                             : cmd      :                  : Defines the second corner of a new Area or Ladder and creates it.
nav_end_deselecting                      : cmd      :                  : Stop continuously removing from the selected set.
nav_end_drag_deselecting                 : cmd      :                  : Stop dragging a selection area.
nav_end_drag_selecting                   : cmd      :                  : Stop dragging a selection area.
nav_end_selecting                        : cmd      :                  : Stop continuously adding to the selected set.
nav_end_shift_xy                         : cmd      :                  : Finish shifting the Selected Set.
nav_flood_select                         : cmd      :                  : Selects the current Area and all Areas connected to it, recursively. To clear a selection, use this command again.
nav_gen_cliffs_approx                    : cmd      :                  : Mark cliff areas, post-processing approximation
nav_generate                             : cmd      :                  : Generate a Navigation Mesh for the current map and save it to disk.
nav_generate_fencetops                   : 1        : , "sv", "cheat"  : Autogenerate nav areas on fence and obstacle tops
nav_generate_fixup_jump_areas            : 1        : , "sv", "cheat"  : Convert obsolete jump areas into 2-way connections
nav_generate_incremental                 : cmd      :                  : Generate a Navigation Mesh for the current map and save it to disk.
nav_generate_incremental_range           : 2000     : , "sv", "cheat"  :
nav_generate_incremental_tolerance       : 0        : , "sv", "cheat"  : Z tolerance for adding new nav areas.
nav_jump                                 : cmd      :                  : Toggles the 'traverse this area by jumping' flag used by the AI system.
nav_ladder_flip                          : cmd      :                  : Flips the selected ladder's direction.
nav_load                                 : cmd      :                  : Loads the Navigation Mesh for the current map.
nav_lower_drag_volume_max                : cmd      :                  : Lower the top of the drag select volume.
nav_lower_drag_volume_min                : cmd      :                  : Lower the bottom of the drag select volume.
nav_make_sniper_spots                    : cmd      :                  : Chops the marked area into disconnected sub-areas suitable for sniper spots.
nav_mark                                 : cmd      :                  : Marks the Area or Ladder under the cursor for manipulation by subsequent editing commands.
nav_mark_attribute                       : cmd      :                  : Set nav attribute for all areas in the selected set.
nav_mark_unnamed                         : cmd      :                  : Mark an Area with no Place name. Useful for finding stray areas missed when Place Painting.
nav_mark_walkable                        : cmd      :                  : Mark the current location as a walkable position. These positions are used as seed locations when sampling the map to generate a Navigation Mesh.
nav_max_view_distance                    : 6000     : , "sv", "cheat"  : Maximum range for precomputed nav mesh visibility (0 = default 1500 units)
nav_max_vis_delta_list_length            : 64       : , "sv", "cheat"  :
nav_merge                                : cmd      :                  : To merge two Areas into one, mark the first Area, highlight the second by pointing your cursor at it, and invoke the merge command.
nav_merge_mesh                           : cmd      :                  : Merges a saved selected set into the current mesh.
nav_no_hostages                          : cmd      :                  : Toggles the 'hostages cannot use this area' flag used by the AI system.
nav_no_jump                              : cmd      :                  : Toggles the 'dont jump in this area' flag used by the AI system.
nav_place_floodfill                      : cmd      :                  : Sets the Place of the Area under the cursor to the curent Place, and 'flood-fills' the Place to all adjacent Areas. Flood-filling stops when it hits an Area with the same Place, or a different Place than that of the initial Area.
nav_place_list                           : cmd      :                  : Lists all place names used in the map.
nav_place_pick                           : cmd      :                  : Sets the current Place to the Place of the Area under the cursor.
nav_place_replace                        : cmd      :                  : Replaces all instances of the first place with the second place.
nav_place_set                            : cmd      :                  : Sets the Place of all selected areas to the current Place.
nav_potentially_visible_dot_tolerance    : 0        : , "sv", "cheat"  :
nav_precise                              : cmd      :                  : Toggles the 'dont avoid obstacles' flag used by the AI system.
nav_quicksave                            : 1        : , "sv", "cheat"  : Set to one to skip the time consuming phases of the analysis.  Useful for data collection and testing.
nav_raise_drag_volume_max                : cmd      :                  : Raise the top of the drag select volume.
nav_raise_drag_volume_min                : cmd      :                  : Raise the bottom of the drag select volume.
nav_recall_selected_set                  : cmd      :                  : Re-selects the stored selected set.
nav_remove_from_selected_set             : cmd      :                  : Remove current area from the selected set.
nav_remove_jump_areas                    : cmd      :                  : Removes legacy jump areas, replacing them with connections.
nav_restart_after_analysis               : 1        : , "sv"           : When nav nav_restart_after_analysis finishes, restart the server.  Turning this off can cause crashes, but is useful for incremental generation.
nav_run                                  : cmd      :                  : Toggles the 'traverse this area by running' flag used by the AI system.
nav_save                                 : cmd      :                  : Saves the current Navigation Mesh to disk.
nav_save_selected                        : cmd      :                  : Writes the selected set to disk for merging into another mesh via nav_merge_mesh.
nav_select_blocked_areas                 : cmd      :                  : Adds all blocked areas to the selected set
nav_select_damaging_areas                : cmd      :                  : Adds all damaging areas to the selected set
nav_select_half_space                    : cmd      :                  : Selects any areas that intersect the given half-space.
nav_select_invalid_areas                 : cmd      :                  : Adds all invalid areas to the Selected Set.
nav_select_larger_than                   : cmd      :                  : Select nav areas where both dimensions are larger than the given size.
nav_select_obstructed_areas              : cmd      :                  : Adds all obstructed areas to the selected set
nav_select_orphans                       : cmd      :                  : Adds all orphan areas to the selected set (highlight a valid area first).
nav_select_overlapping                   : cmd      :                  : Selects nav areas that are overlapping others.
nav_select_radius                        : cmd      :                  : Adds all areas in a radius to the selection set
nav_select_stairs                        : cmd      :                  : Adds all stairway areas to the selected set
nav_selected_set_border_color            : 100      : , "sv", "cheat"  : Color used to draw the selected set borders while editing.
nav_selected_set_color                   : 255      : , "sv", "cheat"  : Color used to draw the selected set background while editing.
nav_set_place_mode                       : cmd      :                  : Sets the editor into or out of Place mode. Place mode allows labelling of Area with Place names.
nav_shift                                : cmd      :                  : Shifts the selected areas by the specified amount
nav_show_approach_points                 : 0        : , "sv", "cheat"  : Show Approach Points in the Navigation Mesh.
nav_show_area_info                       : 0        : , "sv", "cheat"  : Duration in seconds to show nav area ID and attributes while editing
nav_show_compass                         : 0        : , "sv", "cheat"  :
nav_show_continguous                     : 0        : , "sv", "cheat"  : Highlight non-contiguous connections
nav_show_danger                          : 0        : , "sv", "cheat"  : Show current 'danger' levels.
nav_show_dumped_positions                : cmd      :                  : Show the (x,y,z) coordinate positions of the given dump file.
nav_show_func_nav_avoid                  : 0        : , "sv", "cheat"  : Show areas of designer-placed bot avoidance due to func_nav_avoid entities
nav_show_func_nav_prefer                 : 0        : , "sv", "cheat"  : Show areas of designer-placed bot preference due to func_nav_prefer entities
nav_show_func_nav_prerequisite           : 0        : , "sv", "cheat"  : Show areas of designer-placed bot preference due to func_nav_prerequisite entities
nav_show_light_intensity                 : 0        : , "sv", "cheat"  :
nav_show_node_grid                       : 0        : , "sv", "cheat"  :
nav_show_node_id                         : 0        : , "sv", "cheat"  :
nav_show_nodes                           : 0        : , "sv", "cheat"  :
nav_show_player_counts                   : 0        : , "sv", "cheat"  : Show current player counts in each area.
nav_show_potentially_visible             : 0        : , "sv", "cheat"  : Show areas that are potentially visible from the current nav area
nav_simplify_selected                    : cmd      :                  : Chops all selected areas into their component 1x1 areas and re-merges them together into larger areas
nav_slope_limit                          : 0        : , "sv", "cheat"  : The ground unit normal's Z component must be greater than this for nav areas to be generated.
nav_slope_tolerance                      : 0        : , "sv", "cheat"  : The ground unit normal's Z component must be this close to the nav area's Z component to be generated.
nav_snap_to_grid                         : 0        : , "sv", "cheat"  : Snap to the nav generation grid when creating new nav areas
nav_solid_props                          : 0        : , "sv", "cheat"  : Make props solid to nav generation/editing
nav_splice                               : cmd      :                  : To splice, mark an area, highlight a second area, then invoke the splice command to create a new, connected area between them.
nav_split                                : cmd      :                  : To split an Area into two, align the split line using your cursor and invoke the split command.
nav_split_place_on_ground                : 0        : , "sv", "cheat"  : If true, nav areas will be placed flush with the ground when split.
nav_stand                                : cmd      :                  : Toggles the 'stand while hiding' flag used by the AI system.
nav_stop                                 : cmd      :                  : Toggles the 'must stop when entering this area' flag used by the AI system.
nav_store_selected_set                   : cmd      :                  : Stores the current selected set for later retrieval.
nav_strip                                : cmd      :                  : Strips all Hiding Spots, Approach Points, and Encounter Spots from the current Area.
nav_subdivide                            : cmd      :                  : Subdivides all selected areas.
nav_test_node                            : 0        : , "sv", "cheat"  :
nav_test_node_crouch                     : 0        : , "sv", "cheat"  :
nav_test_node_crouch_dir                 : 4        : , "sv", "cheat"  :
nav_test_stairs                          : cmd      :                  : Test the selected set for being on stairs
nav_toggle_deselecting                   : cmd      :                  : Start or stop continuously removing from the selected set.
nav_toggle_in_selected_set               : cmd      :                  : Remove current area from the selected set.
nav_toggle_place_mode                    : cmd      :                  : Toggle the editor into and out of Place mode. Place mode allows labelling of Area with Place names.
nav_toggle_place_painting                : cmd      :                  : Toggles Place Painting mode. When Place Painting, pointing at an Area will 'paint' it with the current Place.
nav_toggle_selected_set                  : cmd      :                  : Toggles all areas into/out of the selected set.
nav_toggle_selecting                     : cmd      :                  : Start or stop continuously adding to the selected set.
nav_transient                            : cmd      :                  : Toggles the 'area is transient and may become blocked' flag used by the AI system.
nav_unmark                               : cmd      :                  : Clears the marked Area or Ladder.
nav_update_blocked                       : cmd      :                  : Updates the blocked/unblocked status for every nav area.
nav_update_lighting                      : cmd      :                  : Recomputes lighting values
nav_update_visibility_on_edit            : 0        : , "sv", "cheat"  : If nonzero editing the mesh will incrementally recompue visibility
nav_use_place                            : cmd      :                  : If used without arguments, all available Places will be listed. If a Place argument is given, the current Place is set.
nav_walk                                 : cmd      :                  : Toggles the 'traverse this area by walking' flag used by the AI system.
nav_warp_to_mark                         : cmd      :                  : Warps the player to the marked area.
nav_world_center                         : cmd      :                  : Centers the nav mesh in the world
nb_allow_avoiding                        : 1        : , "sv", "cheat"  :
nb_allow_climbing                        : 1        : , "sv", "cheat"  :
nb_allow_gap_jumping                     : 1        : , "sv", "cheat"  :
nb_blind                                 : 0        : , "sv", "cheat"  : Disable vision
nb_command                               : cmd      :                  : Sends a command string to all bots
nb_debug                                 : cmd      :                  : Debug NextBots.  Categories are: BEHAVIOR, LOOK_AT, PATH, ANIMATION, LOCOMOTION, VISION, HEARING, EVENTS, ERRORS.
nb_debug_climbing                        : 0        : , "sv", "cheat"  :
nb_debug_filter                          : cmd      :                  : Add items to the NextBot debug filter. Items can be entindexes or part of the indentifier of one or more bots.
nb_debug_history                         : 1        : , "sv", "cheat"  : If true, each bot keeps a history of debug output in memory
nb_debug_known_entities                  : 0        : , "sv", "cheat"  : Show the 'known entities' for the bot that is the current spectator target
nb_delete_all                            : cmd      :                  : Delete all non-player NextBot entities.
nb_force_look_at                         : cmd      :                  : Force selected bot to look at the local player's position
nb_goal_look_ahead_range                 : 50       : , "sv", "cheat"  :
nb_head_aim_resettle_angle               : 100      : , "sv", "cheat"  : After rotating through this angle, the bot pauses to 'recenter' its virtual mouse on its virtual mousepad
nb_head_aim_resettle_time                : 0        : , "sv", "cheat"  : How long the bot pauses to 'recenter' its virtual mouse on its virtual mousepad
nb_head_aim_settle_duration              : 0        : , "sv", "cheat"  :
nb_head_aim_steady_max_rate              : 100      : , "sv", "cheat"  :
nb_ladder_align_range                    : 50       : , "sv", "cheat"  :
nb_last_area_update_tolerance            : 4        : , "sv", "cheat"  : Distance a character needs to travel in order to invalidate cached area
nb_move_to_cursor                        : cmd      :                  : Tell all NextBots to move to the cursor position
nb_path_draw_inc                         : 100      : , "sv", "cheat"  :
nb_path_draw_segment_count               : 100      : , "sv", "cheat"  :
nb_path_segment_influence_radius         : 100      : , "sv", "cheat"  :
nb_player_crouch                         : 0        : , "sv", "cheat"  : Force bots to crouch
nb_player_move                           : 1        : , "sv", "cheat"  : Prevents bots from moving
nb_player_move_direct                    : 0        : , "sv"           :
nb_player_stop                           : 0        : , "sv", "cheat"  : Stop all NextBotPlayers from updating
nb_player_walk                           : 0        : , "sv", "cheat"  : Force bots to walk
nb_saccade_speed                         : 1000     : , "sv", "cheat"  :
nb_saccade_time                          : 0        : , "sv", "cheat"  :
nb_select                                : cmd      :                  : Select the bot you are aiming at for further debug operations.
nb_speed_look_ahead_range                : 150      : , "sv", "cheat"  :
nb_stop                                  : 0        : , "sv", "cheat", "rep" : Stop all NextBots
nb_update_debug                          : 0        : , "sv", "cheat"  :
nb_update_framelimit                     : 15       : , "sv", "cheat"  :
nb_update_frequency                      : 0        : , "sv", "cheat"  :
nb_update_maxslide                       : 2        : , "sv", "cheat"  :
nb_warp_selected_here                    : cmd      :                  : Teleport the selected bot to your cursor position
net_blockmsg                             : 0        : , "cheat"        : Discards incoming message: <0|1|name>
net_channels                             : cmd      :                  : Shows net channel info
net_chokeloop                            : 0        :                  : Apply bandwidth choke to loopback packets
net_compresspackets                      : 1        :                  : Use compression on game packets.
net_compresspackets_minsize              : 1024     :                  : Don't bother compressing packets below this size.
net_compressvoice                        : 0        :                  : Attempt to compress out of band voice payloads (360 only).
net_drawslider                           : 0        :                  : Draw completion slider during signon
net_droppackets                          : 0        : , "cheat"        : Drops next n packets on client
net_fakejitter                           : 0        : , "cheat"        : Jitter fakelag packet time
net_fakelag                              : 0        : , "cheat"        : Lag all incoming network data (including loopback) by this many milliseconds.
net_fakeloss                             : 0        : , "cheat"        : Simulate packet loss as a percentage (negative means drop 1/n packets)
net_maxcleartime                         : 4        :                  : Max # of seconds we can wait for next packets to be sent based on rate setting (0 == no limit).
net_maxfilesize                          : 16       :                  : Maximum allowed file size for uploading in MB
net_maxfragments                         : 1260     :                  : Max fragment bytes per packet
net_maxpacketdrop                        : 5000     :                  : Ignore any packets with the sequence number more than this ahead (0 == no limit)
net_maxroutable                          : 1260     : , "a", "user"    : Requested max packet size before packets are 'split'.
net_queue_trace                          : 0        :                  :
net_queued_packet_thread                 : 1        :                  : Use a high priority thread to send queued packets out instead of sending them each frame.
net_showdrop                             : 0        :                  : Show dropped packets in console
net_showevents                           : 0        : , "cheat"        : Dump game events to console (1=client only, 2=all).
net_showfragments                        : 0        :                  : Show netchannel fragments
net_showmsg                              : 0        :                  : Show incoming message: <0|1|name>
net_showpeaks                            : 0        :                  : Show messages for large packets only: <size>
net_showsplits                           : 0        :                  : Show info about packet splits
net_showtcp                              : 0        :                  : Dump TCP stream summary to console
net_showudp                              : 0        :                  : Dump UDP packets summary to console
net_showudp_wire                         : 0        :                  : Show incoming packet information
net_splitpacket_maxrate                  : 80000    :                  : Max bytes per second when queueing splitpacket chunks
net_splitrate                            : 1        :                  : Number of fragments for a splitpacket that can be sent per frame
net_start                                : cmd      :                  : Inits multiplayer network sockets
net_status                               : cmd      :                  : Shows current network status
net_udp_rcvbuf                           : 131072   :                  : Default UDP receive buffer size
net_usesocketsforloopback                : 0        :                  : Use network sockets layer even for listen server local player's packets (multiplayer only).
net_warningthrottle                      : 5        :                  : Network warning throttling to specified Hz rate
next                                     : 0        : , "cheat"        : Set to 1 to advance to next frame ( when singlestep == 1 )
nextdemo                                 : cmd      :                  : Play next demo in sequence.
nextlevel                                : 0        : , "sv", "nf"     : If set to a valid map name, will trigger a changelevel to the specified map at the end of the round
noclip                                   : cmd      :                  : Toggle. Player becomes non-solid and flies.
notarget                                 : cmd      :                  : Toggle. Player becomes hidden to NPCs.
npc_ally_deathmessage                    : 1        : , "sv", "cheat"  :
npc_height_adjust                        : 1        : , "a", "sv"      : Enable test mode for ik height adjustment
npc_sentences                            : 0        : , "sv"           :
npc_vphysics                             : 0        : , "sv"           :
old_radiusdamage                         : 0        : , "sv", "rep"    :
opt_EnumerateLeavesFastAlgorithm         : 1        :                  : Use the new SIMD version of CEngineBSPTree::EnumerateLeavesInBox.
option_duck_method                       : 1        : , "a", "sv", "rep" :
panel_test_title_safe                    : 0        : , "cheat"        : Test vgui panel positioning with title safe indentation
particle_test_attach_attachment          : 0        : , "sv", "cheat"  : Attachment index for attachment mode
particle_test_attach_mode                : 0        : , "sv", "cheat"  : Possible Values: 'start_at_attachment', 'follow_attachment', 'start_at_origin', 'follow_origin'
particle_test_file                       : 0        : , "sv", "cheat"  : Name of the particle system to dynamically spawn
particle_test_start                      : cmd      :                  : Dispatches the test particle system with the parameters specified in particle_test_file,  particle_test_attach_mode and particle_test_attach_param on the entity the player is looking at.  Arguments:    {entity_name} / {class_name} / no argument picks what player is looking at
particle_test_stop                       : cmd      :                  : Stops all particle systems on the selected entities.  Arguments:    {entity_name} / {class_name} / no argument picks what player is looking at
password                                 : 0        : , "a", "norecord" : Current server access password
path                                     : cmd      :                  : Show the engine filesystem path.
pause                                    : cmd      :                  : Toggle the server pause state.
PerfMark                                 : cmd      :                  : inserts a telemetry marker into the stream. If args are provided, they will be included.
perfui                                   : cmd      :                  : Show/hide the level performance tools UI.
phys_impactforcescale                    : 1        : , "sv"           :
phys_penetration_error_time              : 10       : , "sv"           : Controls the duration of vphysics penetration error boxes.
phys_pushscale                           : 1        : , "sv", "rep"    :
phys_speeds                              : 0        : , "sv"           :
phys_stressbodyweights                   : 5        : , "sv"           :
phys_timescale                           : 1        : , "sv"           : Scale time for physics
phys_upimpactforcescale                  : 0        : , "sv"           :
physics_budget                           : cmd      :                  : Times the cost of each active object
physics_constraints                      : cmd      :                  : Highlights constraint system graph for an entity
physics_debug_entity                     : cmd      :                  : Dumps debug info for an entity
physics_highlight_active                 : cmd      :                  : Turns on the absbox for all active physics objects
physics_report_active                    : cmd      :                  : Lists all active physics objects
physics_select                           : cmd      :                  : Dumps debug info for an entity
physicsshadowupdate_render               : 0        : , "sv"           :
picker                                   : cmd      :                  : Toggles 'picker' mode.  When picker is on, the bounding box, pivot and debugging text is displayed for whatever entity the player is looking at.  Arguments: full - enables all debug information
ping                                     : cmd      :                  : Display ping to server.
pipeline_static_props                    : 1        :                  :
play                                     : cmd      :                  : Play a sound.
playdemo                                 : cmd      :                  : Play a recorded demo file (.dem ).
player_debug_print_damage                : 0        : , "sv", "cheat"  : When true, print amount and type of all damage received by player to console.
player_old_armor                         : 0        : , "sv"           :
playflush                                : cmd      :                  : Play a sound, reloading from disk in case of changes.
playvol                                  : cmd      :                  : Play a sound at a specified volume.
plugin_load                              : cmd      :                  : plugin_load <filename> : loads a plugin
plugin_pause                             : cmd      :                  : plugin_pause <index> : pauses a loaded plugin
plugin_pause_all                         : cmd      :                  : pauses all loaded plugins
plugin_print                             : cmd      :                  : Prints details about loaded plugins
plugin_unload                            : cmd      :                  : plugin_unload <index> : unloads a plugin
plugin_unpause                           : cmd      :                  : plugin_unpause <index> : unpauses a disabled plugin
plugin_unpause_all                       : cmd      :                  : unpauses all disabled plugins
print_colorcorrection                    : cmd      :                  : Display the color correction layer information.
progress_enable                          : cmd      :                  :
prop_active_gib_limit                    : 999999   : , "sv"           :
prop_active_gib_max_fade_time            : 999999   : , "sv"           :
prop_crosshair                           : cmd      :                  : Shows name for prop looking at
prop_debug                               : cmd      :                  : Toggle prop debug mode. If on, props will show colorcoded bounding boxes. Red means ignore all damage. White means respond physically to damage but never break. Green maps health in the range of 100 down to 1.
prop_dynamic_create                      : cmd      :                  : Creates a dynamic prop with a specific .mdl aimed away from where the player is looking.  Arguments: {.mdl name}
prop_physics_create                      : cmd      :                  : Creates a physics prop with a specific .mdl aimed away from where the player is looking.  Arguments: {.mdl name}
props_break_max_pieces                   : -1       : , "sv"           : Maximum prop breakable piece count (-1 = model default)
props_break_max_pieces_perframe          : -1       : , "sv", "rep"    : Maximum prop breakable piece count per frame (-1 = model default)
quit                                     : cmd      :                  : Exit the engine.
r_3dnow                                  : cmd      :                  : Enable/disable 3DNow code
r_AirboatViewDampenDamp                  : 1        : , "sv", "cheat", "nf", "rep" :
r_AirboatViewDampenFreq                  : 7        : , "sv", "cheat", "nf", "rep" :
r_AirboatViewZHeight                     : 0        : , "sv", "cheat", "nf", "rep" :
r_ambientboost                           : 1        : , "a"            : Set to boost ambient term if it is totally swamped by local lights
r_ambientfactor                          : 5        : , "a"            : Boost ambient cube by no more than this factor
r_ambientfraction                        : 0        : , "cheat"        : Fraction of direct lighting that ambient cube must be below to trigger boosting
r_ambientlightingonly                    : 0        : , "cheat"        : Set this to 1 to light models with only ambient lighting (and no static lighting).
r_ambientmin                             : 0        : , "a"            : Threshold above which ambient cube will not boost (i.e. it's already sufficiently bright
r_aspectratio                            : 0        : , "cheat"        :
r_avglight                               : 1        : , "cheat"        :
r_avglightmap                            : 0        : , "cheat"        :
r_bloomtintb                             : 0        :                  :
r_bloomtintexponent                      : 2        :                  :
r_bloomtintg                             : 0        :                  :
r_bloomtintr                             : 0        :                  :
r_cleardecals                            : cmd      :                  : Usage r_cleardecals <permanent>.
r_ClipAreaPortals                        : 1        : , "cheat"        :
r_colorstaticprops                       : 0        : , "cheat"        :
r_debugrandomstaticlighting              : 0        : , "cheat"        : Set to 1 to randomize static lighting for debugging.  Must restart for change to take affect.
r_decal_cover_count                      : 4        :                  :
r_decal_overlap_area                     : 0        :                  :
r_decal_overlap_count                    : 3        :                  :
r_decals                                 : 2048     :                  :
r_decalstaticprops                       : 1        :                  : Decal static props test
r_DispBuildable                          : 0        : , "cheat"        :
r_DispDrawAxes                           : 0        :                  :
r_DispWalkable                           : 0        : , "cheat"        :
r_drawbatchdecals                        : 1        :                  : Render decals batched.
r_DrawBeams                              : 1        : , "cheat"        : 0=Off, 1=Normal, 2=Wireframe
r_drawbrushmodels                        : 1        : , "cheat"        : Render brush models. 0=Off, 1=Normal, 2=Wireframe
r_drawclipbrushes                        : 0        : , "cheat"        : Draw clip brushes (red=NPC+player, pink=player, purple=NPC)
r_drawdecals                             : 1        : , "cheat"        : Render decals.
r_DrawDisp                               : 1        : , "cheat"        : Toggles rendering of displacment maps
r_drawentities                           : 1        : , "cheat"        :
r_drawfuncdetail                         : 1        : , "cheat"        : Render func_detail
r_drawleaf                               : -1       : , "cheat"        : Draw the specified leaf.
r_drawlightcache                         : 0        : , "cheat"        : 0: off 1: draw light cache entries 2: draw rays
r_drawlightinfo                          : 0        : , "cheat"        :
r_drawlights                             : 0        : , "cheat"        :
r_drawmodeldecals                        : 1        :                  :
r_DrawModelLightOrigin                   : 0        : , "cheat"        :
r_drawmodelstatsoverlay                  : 0        : , "cheat"        :
r_drawmodelstatsoverlaydistance          : 500      : , "cheat"        :
r_drawmodelstatsoverlaymax               : 1        : , "a"            : time in milliseconds beyond which a model overlay is fully red in r_drawmodelstatsoverlay 2
r_drawmodelstatsoverlaymin               : 0        : , "a"            : time in milliseconds that a model must take to render before showing an overlay in r_drawmodelstatsoverlay 2
r_DrawPortals                            : 0        : , "cheat"        :
r_drawskybox                             : 1        : , "cheat"        :
r_DrawSpecificStaticProp                 : -1       :                  :
r_drawstaticprops                        : 1        : , "cheat"        : 0=Off, 1=Normal, 2=Wireframe
r_drawtranslucentworld                   : 1        : , "cheat"        :
r_drawvgui                               : 1        : , "cheat"        : Enable the rendering of vgui panels
r_drawworld                              : 1        : , "cheat"        : Render the world.
r_dscale_basefov                         : 90       : , "cheat"        :
r_dscale_fardist                         : 2000     : , "cheat"        :
r_dscale_farscale                        : 4        : , "cheat"        :
r_dscale_neardist                        : 100      : , "cheat"        :
r_dscale_nearscale                       : 1        : , "cheat"        :
r_dynamic                                : 1        :                  :
r_dynamiclighting                        : 1        : , "cheat"        :
r_eyeglintlodpixels                      : 20       : , "cheat"        : The number of pixels wide an eyeball has to be before rendering an eyeglint.  Is a floating point value.
r_eyemove                                : 1        : , "a"            :
r_eyes                                   : 1        :                  :
r_eyeshift_x                             : 0        : , "a"            :
r_eyeshift_y                             : 0        : , "a"            :
r_eyeshift_z                             : 0        : , "a"            :
r_eyesize                                : 0        : , "a"            :
r_fastzreject                            : 0        :                  : Activate/deactivates a fast z-setting algorithm to take advantage of hardware with fast z reject. Use -1 to default to hardware settings
r_fastzrejectdisp                        : 0        :                  : Activates/deactivates fast z rejection on displacements (360 only). Only active when r_fastzreject is on.
r_flashlightclip                         : 0        : , "cheat"        :
r_flashlightculldepth                    : 1        :                  :
r_flashlightdepthtexture                 : 0        :                  :
r_flashlightdrawclip                     : 0        : , "cheat"        :
r_flashlightdrawdepth                    : 0        :                  :
r_flashlightdrawfrustumbbox              : 0        :                  :
r_flashlightdrawsweptbbox                : 0        :                  :
r_flashlightnodraw                       : 0        :                  :
r_flashlightrender                       : 1        :                  :
r_flashlightrendermodels                 : 1        :                  :
r_flashlightrenderworld                  : 1        :                  :
r_flashlightscissor                      : 1        :                  :
r_flashlightupdatedepth                  : 1        :                  :
r_flex                                   : 1        :                  :
r_flushlod                               : cmd      :                  : Flush and reload LODs.
r_frustumcullworld                       : 1        :                  :
r_glint_alwaysdraw                       : 0        :                  :
r_glint_procedural                       : 0        :                  :
r_hunkalloclightmaps                     : 1        :                  :
r_hwmorph                                : 1        : , "cheat"        :
r_itemblinkmax                           : 0        : , "cheat"        :
r_itemblinkrate                          : 4        : , "cheat"        :
r_JeepFOV                                : 90       : , "sv", "cheat", "rep" :
r_JeepViewDampenDamp                     : 1        : , "sv", "cheat", "nf", "rep" :
r_JeepViewDampenFreq                     : 7        : , "sv", "cheat", "nf", "rep" :
r_JeepViewZHeight                        : 10       : , "sv", "cheat", "nf", "rep" :
r_lightaverage                           : 1        :                  : Activates/deactivate light averaging
r_lightcache_numambientsamples           : 162      : , "cheat"        : number of random directions to fire rays when computing ambient lighting
r_lightcache_zbuffercache                : 0        :                  :
r_lightcachecenter                       : 1        : , "cheat"        :
r_lightcachemodel                        : -1       : , "cheat"        :
r_lightinterp                            : 5        : , "cheat"        : Controls the speed of light interpolation, 0 turns off interpolation
r_lightmap                               : -1       : , "cheat"        :
r_lightstyle                             : -1       : , "cheat"        :
r_lightwarpidentity                      : 0        : , "cheat"        :
r_lockpvs                                : 0        : , "cheat"        : Lock the PVS so you can fly around and inspect what is being drawn.
r_lod                                    : -1       :                  :
r_maxdlights                             : 32       :                  :
r_maxmodeldecal                          : 50       :                  :
r_maxnewsamples                          : 6        :                  :
r_maxsampledist                          : 128      :                  :
r_minnewsamples                          : 3        :                  :
r_modelwireframedecal                    : 0        : , "cheat"        :
r_nohw                                   : 0        : , "cheat"        :
r_norefresh                              : 0        :                  :
r_nosw                                   : 0        : , "cheat"        :
r_novis                                  : 0        : , "cheat"        : Turn off the PVS.
r_occludeemaxarea                        : 0        :                  : Prevents occlusion testing for entities that take up more than X% of the screen. 0 means use whatever the level said to use.
r_occluderminarea                        : 0        :                  : Prevents this occluder from being used if it takes up less than X% of the screen. 0 means use whatever the level said to use.
r_occludermincount                       : 0        :                  : At least this many occluders will be used, no matter how big they are.
r_occlusion                              : 1        :                  : Activate/deactivate the occlusion system.
r_occlusionspew                          : 0        : , "cheat"        : Activate/deactivates spew about what the occlusion system is doing.
r_oldlightselection                      : 0        : , "cheat"        : Set this to revert to HL2's method of selecting lights
r_overlayfadeenable                      : 0        :                  :
r_overlayfademax                         : 2000     :                  :
r_overlayfademin                         : 1750     :                  :
r_overlaywireframe                       : 0        :                  :
r_partition_level                        : -1       : , "cheat"        : Displays a particular level of the spatial partition system. Use -1 to disable it.
r_portalsopenall                         : 0        : , "cheat"        : Open all portals
r_printdecalinfo                         : cmd      :                  :
r_proplightingfromdisk                   : 1        :                  : 0=Off, 1=On, 2=Show Errors
r_proplightingpooling                    : -1       : , "cheat"        : 0 - off, 1 - static prop color meshes are allocated from a single shared vertex buffer (on hardware that supports stream offset)
r_queued_decals                          : 0        :                  : Offloads a bit of decal rendering setup work to the material system queue when enabled.
r_radiosity                              : 4        : , "cheat"        : 0: no radiosity 1: radiosity with ambient cube (6 samples) 2: radiosity with 162 samples 3: 162 samples for static props, 6 samples for everything else
r_randomflex                             : 0        : , "cheat"        :
r_renderoverlayfragment                  : 1        :                  :
r_rimlight                               : 1        :                  :
r_rootlod                                : 0        : , "a"            : Root LOD
r_shadowids                              : 0        : , "cheat"        :
r_shadowrendertotexture                  : 0        :                  :
r_shadows                                : 1        :                  :
r_shadows_gamecontrol                    : -1       : , "cheat"        :
r_shadowwireframe                        : 0        : , "cheat"        :
r_showenvcubemap                         : 0        : , "cheat"        :
r_ShowViewerArea                         : 0        :                  :
r_showz_power                            : 1        : , "cheat"        :
r_skin                                   : 0        : , "cheat"        :
r_snapportal                             : -1       :                  :
r_spray_lifetime                         : 2        :                  : Number of rounds player sprays are visible
r_sse2                                   : cmd      :                  : Enable/disable SSE2 code
r_staticprop_lod                         : -1       :                  :
r_staticpropinfo                         : 0        :                  :
r_studio_stats                           : 0        : , "cheat"        :
r_teeth                                  : 1        :                  :
r_unloadlightmaps                        : 0        : , "cheat"        :
r_vehicleBrakeRate                       : 1        : , "sv", "cheat"  :
r_VehicleViewDampen                      : 1        : , "sv", "cheat", "nf", "rep" :
r_visambient                             : 0        :                  : Draw leaf ambient lighting samples.  Needs mat_leafvis 1 to work
r_visocclusion                           : 0        : , "cheat"        : Activate/deactivate wireframe rendering of what the occlusion system is doing.
r_visualizelighttraces                   : 0        : , "cheat"        :
r_visualizelighttracesshowfulltrace      : 0        : , "cheat"        :
r_visualizetraces                        : 0        : , "cheat"        :
r_waterforceexpensive                    : 0        : , "a"            :
r_waterforcereflectentities              : 0        :                  :
r_worldlightmin                          : 0        :                  :
r_worldlights                            : 4        :                  : number of world lights to use per vertex
rate                                     : 80000    : , "a", "user"    : Max bytes/sec the host can receive data
rcon                                     : cmd      :                  : Issue an rcon command.
rcon_address                             : 0        : , "norecord"     : Address of remote server if sending unconnected rcon commands (format x.x.x.x:p)
rcon_password                            : 0        : , "norecord"     : remote console password.
rebuy                                    : cmd      :                  : Attempt to repurchase items with the order listed in cl_rebuy
recompute_speed                          : cmd      :                  : Recomputes clock speed (for debugging purposes).
record                                   : cmd      :                  : Record a demo.
redirect                                 : cmd      :                  : Redirect client to specified server.
reload                                   : cmd      :                  : Reload the most recent saved game (add setpos to jump to current view position on reload).
reload_materials                         : 0        :                  :
removeid                                 : cmd      :                  : Remove a user ID from the ban list.
removeip                                 : cmd      :                  : Remove an IP address from the ban list.
replay_debug                             : 0        : , "norecord"     :
replay_ignorereplayticks                 : 0        :                  :
report_entities                          : cmd      :                  : Lists all entities
report_simthinklist                      : cmd      :                  : Lists all simulating/thinking entities
report_soundpatch                        : cmd      :                  : reports sound patch count
report_touchlinks                        : cmd      :                  : Lists all touchlinks
respawn_entities                         : cmd      :                  : Respawn all the entities in the map.
restart                                  : cmd      :                  : Restart the game on the same level (add setpos to jump to current view position on restart).
retry                                    : cmd      :                  : Retry connection to last server.
room_type                                : 0        : , "demo"         :
rr_debug_qa                              : 0        : , "sv"           : Set to 1 to see debug related to the Question & Answer system used to create conversations between allied NPCs.
rr_debugresponses                        : 0        : , "sv"           : Show verbose matching output (1 for simple, 2 for rule scoring). If set to 3, it will only show response success/failure for npc_selected NPCs.
rr_debugrule                             : 0        : , "sv"           : If set to the name of the rule, that rule's score will be shown whenever a concept is passed into the response rules system.
rr_dumpresponses                         : 0        : , "sv"           : Dump all response_rules.txt and rules (requires restart)
rr_reloadresponsesystems                 : cmd      :                  : Reload all response system scripts.
save                                     : cmd      :                  : Saves current game.
save_async                               : 1        :                  :
save_asyncdelay                          : 0        :                  : For testing, adds this many milliseconds of delay to the save operation.
save_console                             : 0        :                  : Autosave on the PC behaves like it does on the consoles.
save_disable                             : 0        :                  :
save_finish_async                        : cmd      :                  :
save_history_count                       : 1        :                  : Keep this many old copies in history of autosaves and quicksaves.
save_huddelayframes                      : 1        :                  : Number of frames to defer for drawing the Saving message.
save_in_memory                           : 0        :                  : Set to 1 to save to memory instead of disk (Xbox 360)
save_noxsave                             : 0        :                  :
save_screenshot                          : 1        :                  : 0 = none, 1 = non-autosave, 2 = always
save_spew                                : 0        :                  :
say                                      : cmd      :                  : Display player message
say_team                                 : cmd      :                  : Display player message to team
scene_async_prefetch_spew                : 0        : , "sv"           : Display async .ani file loading info.
scene_clamplookat                        : 1        : , "sv"           : Clamp head turns to a max of 20 degrees per think.
scene_clientflex                         : 1        : , "sv", "rep"    : Do client side flex animation.
scene_flatturn                           : 1        : , "sv"           :
scene_flush                              : cmd      :                  : Flush all .vcds from the cache and reload from disk.
scene_forcecombined                      : 0        : , "sv"           : When playing back, force use of combined .wav files even in english.
scene_maxcaptionradius                   : 1200     : , "sv"           : Only show closed captions if recipient is within this many units of speaking actor (0==disabled).
scene_print                              : 0        : , "sv", "rep"    : When playing back a scene, print timing and event info to console.
scene_showfaceto                         : 0        : , "a", "sv"      : When playing back, show the directions of faceto events.
scene_showlook                           : 0        : , "a", "sv"      : When playing back, show the directions of look events.
scene_showmoveto                         : 0        : , "a", "sv"      : When moving, show the end location.
scene_showunlock                         : 0        : , "a", "sv"      : Show when a vcd is playing but normal AI is running.
screenshot                               : cmd      :                  : Take a screenshot.
server_game_time                         : cmd      :                  : Gives the game time in seconds (server's curtime)
servercfgfile                            : 0        : , "sv"           :
setang                                   : cmd      :                  : Snap player eyes to specified pitch yaw <roll:optional> (must have sv_cheats).
setang_exact                             : cmd      :                  : Snap player eyes and orientation to specified pitch yaw <roll:optional> (must have sv_cheats).
setinfo                                  : cmd      :                  : Adds a new user info value
setmodel                                 : cmd      :                  : Changes's player's model
setpause                                 : cmd      :                  : Set the pause state of the server.
setpos                                   : cmd      :                  : Move player to specified origin (must have sv_cheats).
setpos_exact                             : cmd      :                  : Move player to an exact specified origin (must have sv_cheats).
shake                                    : cmd      :                  : Shake the screen.
+showbudget                              : cmd      :                  :
-showbudget                              : cmd      :                  :
showbudget_texture                       : 0        : , "cheat"        : Enable the texture budget panel.
+showbudget_texture                      : cmd      :                  :
-showbudget_texture                      : cmd      :                  :
+showbudget_texture_global               : cmd      :                  :
-showbudget_texture_global               : cmd      :                  :
showbudget_texture_global_sum            : 0        :                  :
showconsole                              : cmd      :                  : Show the console.
showhitlocation                          : 0        : , "sv"           :
showtriggers                             : 0        : , "sv", "cheat"  : Shows trigger brushes
showtriggers_toggle                      : cmd      :                  : Toggle show triggers
+showvprof                               : cmd      :                  :
-showvprof                               : cmd      :                  :
simple_bot_add                           : cmd      :                  : Add a simple bot.
singlestep                               : 0        : , "cheat"        : Run engine in single step mode ( set next to 1 to advance a frame )
sk_ally_regen_time                       : 0        : , "sv"           : Time taken for an ally to regenerate a point of health.
sk_autoaim_mode                          : 1        : , "a", "sv", "rep" :
sk_npc_arm                               : 1        : , "sv"           :
sk_npc_chest                             : 1        : , "sv"           :
sk_npc_head                              : 2        : , "sv"           :
sk_npc_leg                               : 1        : , "sv"           :
sk_npc_stomach                           : 1        : , "sv"           :
sk_player_arm                            : 1        : , "sv"           :
sk_player_chest                          : 1        : , "sv"           :
sk_player_head                           : 2        : , "sv"           :
sk_player_leg                            : 1        : , "sv"           :
sk_player_stomach                        : 1        : , "sv"           :
skill                                    : 1        : , "a"            : Game skill level (1-3).
skip_next_map                            : cmd      :                  : Skips the next map in the map rotation for the server.
smoothstairs                             : 1        : , "sv", "rep"    : Smooth player eye z coordinate when traversing stairs.
snd_async_flush                          : cmd      :                  : Flush all unlocked async audio data
snd_async_fullyasync                     : 0        :                  : All playback is fully async (sound doesn't play until data arrives).
snd_async_minsize                        : 262144   :                  :
snd_async_showmem                        : cmd      :                  : Show async memory stats
snd_async_spew                           : 0        :                  : Spew all async sound reads, including success
snd_async_spew_blocking                  : 1        :                  : Spew message to console any time async sound loading blocks on file i/o. ( 0=Off, 1=With -steam only, 2=Always
snd_async_stream_spew                    : 0        :                  : Spew streaming info ( 0=Off, 1=streams, 2=buffers
snd_buildcache                           : cmd      :                  : <directory or VPK filename>  Rebulds sound cache for a given search path.
snd_cull_duplicates                      : 0        :                  : If nonzero, aggressively cull duplicate sounds during mixing. The number specifies the number of duplicates allowed to be played.
snd_defer_trace                          : 1        :                  :
snd_delay_sound_shift                    : 0        :                  :
snd_disable_mixer_duck                   : 0        :                  :
snd_duckerattacktime                     : 0        : , "a"            :
snd_duckerreleasetime                    : 2        : , "a"            :
snd_duckerthreshold                      : 0        : , "a"            :
snd_ducktovolume                         : 0        : , "a"            :
snd_dumpclientsounds                     : cmd      :                  : Dump sounds to VXConsole
snd_foliage_db_loss                      : 4        : , "cheat"        :
snd_gain                                 : 1        : , "cheat"        :
snd_gain_max                             : 1        : , "cheat"        :
snd_gain_min                             : 0        : , "cheat"        :
snd_legacy_surround                      : 0        : , "a"            :
snd_lockpartial                          : 1        :                  :
snd_mix_async                            : 0        :                  :
snd_mixahead                             : 0        : , "a"            :
snd_musicvolume                          : 1        : , "a"            : Music volume
snd_mute_losefocus                       : 1        : , "a"            :
snd_noextraupdate                        : 0        :                  :
snd_obscured_gain_dB                     : -2       : , "cheat"        :
snd_pitchquality                         : 1        : , "a"            :
snd_profile                              : 0        : , "demo"         :
snd_refdb                                : 60       : , "cheat"        :
snd_refdist                              : 36       : , "cheat"        :
snd_restart                              : cmd      :                  : Restart sound system.
snd_show                                 : 0        : , "cheat"        : Show sounds info
snd_showclassname                        : 0        :                  :
snd_showmixer                            : 0        :                  :
snd_showstart                            : 0        : , "cheat"        :
snd_ShowThreadFrameTime                  : 0        :                  :
snd_soundmixer                           : 0        :                  :
snd_spatialize_roundrobin                : 0        :                  : Lowend optimization: if nonzero, spatialize only a fraction of sound channels each frame. 1/2^x of channels will be spatialized per frame.
snd_surround_speakers                    : -1       :                  :
snd_visualize                            : 0        : , "cheat"        : Show sounds location in world
snd_vox_captiontrace                     : 0        :                  : Shows sentence name for sentences which are set not to show captions.
snd_vox_globaltimeout                    : 300      :                  :
snd_vox_sectimetout                      : 300      :                  :
snd_vox_seqtimetout                      : 300      :                  :
sndplaydelay                             : cmd      :                  : Usage:  sndplaydelay delay_in_sec (negative to skip ahead) soundname
soundfade                                : cmd      :                  : Fade client volume.
soundinfo                                : cmd      :                  : Describe the current sound device.
soundlist                                : cmd      :                  : List all known sounds.
soundpatch_captionlength                 : 2        : , "sv", "rep"    : How long looping soundpatch captions should display for.
soundscape_debug                         : 0        : , "sv", "cheat"  : When on, draws lines to all env_soundscape entities. Green lines show the active soundscape, red lines show soundscapes that aren't in range, and white lines show soundscapes that are in range, but not the active soundscape.
soundscape_flush                         : cmd      :                  : Flushes the server & client side soundscapes
speak                                    : cmd      :                  : Play a constructed sentence.
spec_freeze_time                         : 5        : , "sv", "cheat", "rep" : Time spend frozen in observer freeze cam.
spec_freeze_traveltime                   : 0        : , "sv", "cheat", "rep" : Time taken to zoom in to frame a target in observer freeze cam.
spew_consolelog_to_debugstring           : 0        :                  : Send console log to PLAT_DebugString()
spike                                    : cmd      :                  : generates a fake spike
star_memory                              : cmd      :                  : Dump memory stats
startdemos                               : cmd      :                  : Play demos in demo sequence.
startmovie                               : cmd      :                  : Start recording movie frames.
startupmenu                              : cmd      :                  : Opens initial menu screen and loads the background bsp, but only if no other level is being loaded, and we're not in developer mode.
stats                                    : cmd      :                  : Prints server performance variables
status                                   : cmd      :                  : Display map and connection status.
step_spline                              : 0        : , "sv"           :
stop                                     : cmd      :                  : Finish recording demo.
stopdemo                                 : cmd      :                  : Stop playing back a demo.
stopsound                                : cmd      :                  :
studio_queue_mode                        : 1        :                  :
stuffcmds                                : cmd      :                  : Parses and stuffs command line + commands to command buffer.
suitvolume                               : 0        : , "a", "sv"      :
surfaceprop                              : cmd      :                  : Reports the surface properties at the cursor
sv_accelerate                            : 5        : , "sv", "nf", "rep" :
sv_airaccelerate                         : 10       : , "sv", "nf", "rep" :
sv_allow_color_correction                : 1        : , "rep"          : Allow or disallow clients to use color correction on this server.
sv_allow_point_servercommand             : 0        : , "sv"           : Allow use of point_servercommand entities in map. Potentially dangerous for untrusted maps.   disallow : Always disallow   always   : Allow for all maps
sv_allow_voice_from_file                 : 1        : , "rep"          : Allow or disallow clients from using voice_inputfromfile on this server.
sv_allow_votes                           : 1        : , "sv"           : Allow voting?
sv_allow_wait_command                    : 1        : , "rep"          : Allow or disallow the wait command on clients connected to this server.
sv_allowdownload                         : 1        :                  : Allow clients to download files
sv_allowminmodels                        : 1        : , "sv", "nf", "rep" : Allow or disallow the use of cl_minmodels on this server.
sv_allowupload                           : 1        :                  : Allow clients to upload customizations files
sv_alltalk                               : 0        : , "sv", "nf", "rep" : Players can hear all other players, no team restrictions
sv_alternateticks                        : 0        : , "sp"           : If set, server only simulates entities on even numbered ticks.
sv_autosave                              : 1        :                  : Set to 1 to autosave game on level transition. Does not affect autosave triggers.
sv_backspeed                             : 0        : , "a", "sv", "rep" : How much to slow down backwards motion
sv_benchmark_autovprofrecord             : 0        : , "sv"           : If running a benchmark and this is set, it will record a vprof file over the duration of the benchmark with filename benchmark.vprof.
sv_benchmark_force_start                 : cmd      :                  : Force start the benchmark. This is only for debugging. It's better to set sv_benchmark to 1 and restart the level.
sv_benchmark_numticks                    : 3300     : , "sv"           : If > 0, then it only runs the benchmark for this # of ticks.
sv_bonus_challenge                       : 0        : , "sv", "rep"    : Set to values other than 0 to select a bonus map challenge type.
sv_bounce                                : 0        : , "sv", "nf", "rep" : Bounce multiplier for when physically simulated objects collide with other objects.
sv_cacheencodedents                      : 1        :                  : If set to 1, does an optimization to prevent extra SendTable_Encode calls.
sv_cheats                                : 0        : , "nf", "rep"    : Allow cheats on server
sv_clearhinthistory                      : cmd      :                  : Clear memory of server side hints displayed to the player.
sv_client_cmdrate_difference             : 20       : , "rep"          : cl_cmdrate is moved to within sv_client_cmdrate_difference units of cl_updaterate before it is clamped between sv_mincmdrate and sv_maxcmdrate.
sv_client_max_interp_ratio               : 5        : , "rep"          : This can be used to limit the value of cl_interp_ratio for connected clients (only while they are connected). If sv_client_min_interp_ratio is -1, then this cvar has no effect.
sv_client_min_interp_ratio               : 1        : , "rep"          : This can be used to limit the value of cl_interp_ratio for connected clients (only while they are connected).               -1 = let clients set cl_interp_ratio to anything  any other value = set minimum value for cl_interp_ratio
sv_client_predict                        : -1       : , "rep"          : This can be used to force the value of cl_predict for connected clients (only while they are connected).    -1 = let clients set cl_predict to anything     0 = force cl_predict to 0     1 = force cl_predict to 1
sv_clockcorrection_msecs                 : 60       : , "sv"           : The server tries to keep each player's m_nTickBase withing this many msecs of the server absolute tickcount
sv_competitive_minspec                   : 0        : , "sv", "nf", "rep" : Enable to force certain client convars to minimum/maximum values to help prevent competitive advantages:   r_drawdetailprops = 1   r_staticprop_lod = minimum -1 maximum 3   fps_max minimum 59 (0 works too)   cl_detailfade minimum 400   cl_detaildist minimum 1200   cl_interp_ratio = minimum 1 maximum 2   cl_interp = minimum 0 maximum 0.031
sv_compressstringtablebaselines_threshold : 2048     :                  : Minimum size (in bytes) for stringtablebaseline buffer to be compressed.
sv_consistency                           : 1        : , "rep"          : Legacy variable with no effect!  This was deleted and then added as a temporary kludge to prevent players from being banned by servers running old versions of SMAC
sv_contact                               : 0        : , "nf"           : Contact email for server sysop
sv_debug_player_use                      : 0        : , "sv", "rep"    : Visualizes +use logic. Green cross=trace success, Red cross=trace too far, Green box=radius success
sv_debugmanualmode                       : 0        :                  : Make sure entities correctly report whether or not their network data has changed.
sv_debugroundstats                       : 0        : , "sv"           : A temporary variable that will print extra information about stats upload which may be useful in debugging any problems.
sv_debugtempentities                     : 0        :                  : Show temp entity bandwidth usage.
sv_deltaprint                            : 0        :                  : Print accumulated CalcDelta profiling data (only if sv_deltatime is on)
sv_deltatime                             : 0        :                  : Enable profiling of CalcDelta calls
sv_disable_querycache                    : 0        : , "sv", "cheat"  : debug - disable trace query cache
sv_disablefreezecam                      : 0        : , "sv", "rep"    : Turn on/off freezecam on server
sv_downloadurl                           : 0        : , "rep"          : Location from which clients can download missing files
sv_dump_edicts                           : cmd      :                  : Display a list of edicts allocated on the server.
sv_dumpstringtables                      : 0        : , "cheat"        :
sv_enableboost                           : 0        : , "sv", "nf", "rep" : Allow boost exploits
sv_enablebunnyhopping                    : 0        : , "sv", "nf", "rep" :
sv_enableoldqueries                      : 0        :                  : Enable support for old style (HL1) server queries
sv_filterban                             : 1        :                  : Set packet filtering by IP mode
sv_footsteps                             : 1        : , "sv", "nf", "rep" : Play footstep sound for players
sv_forcepreload                          : 0        : , "a"            : Force server side preloading.
sv_friction                              : 4        : , "sv", "nf", "rep" : World friction.
sv_gravity                               : 800      : , "sv", "nf", "rep" : World gravity.
sv_hudhint_sound                         : 1        : , "sv", "rep"    :
sv_ignoregrenaderadio                    : 0        : , "sv"           : Turn off Fire in the hole messages
sv_ladder_angle                          : 0        : , "sv", "rep"    : Cos of angle of incidence to ladder perpendicular for applying ladder_dampen
sv_ladder_dampen                         : 0        : , "sv", "rep"    : Amount to dampen perpendicular movement on a ladder
sv_lan                                   : 0        :                  : Server is a lan server ( no heartbeat, no authentication, no non-class C addresses )
sv_legacy_grenade_damage                 : 0        : , "sv", "rep"    : Enable to replicate grenade damage behavior of the original Counter-Strike Source game.
sv_log_onefile                           : 0        : , "a"            : Log server information to only one file.
sv_logbans                               : 0        : , "a"            : Log server bans in the server logs.
sv_logblocks                             : 0        :                  : If true when log when a query is blocked (can cause very large log files)
sv_logdownloadlist                       : 1        :                  :
sv_logecho                               : 1        : , "a"            : Echo log information to the console.
sv_logfile                               : 1        : , "a"            : Log server information in the log file.
sv_logfilecompress                       : 0        : , "a"            : Gzip compress logfile and rename to logfilename.log.gz on close.
sv_logfilename_format                    : 0        : , "a"            : Log filename format. See strftime for formatting codes.
sv_logflush                              : 0        : , "a"            : Flush the log file to disk on each write (slow).
sv_logsdir                               : 0        : , "a"            : Folder in the game directory where server logs will be stored.
sv_logsecret                             : 0        :                  : If set then include this secret when doing UDP logging (will use 0x53 as packet type, not usual 0x52)
sv_lowedict_action                       : 0        :                  : 0 - no action, 1 - warn to log file, 2 - attempt to restart the game, if applicable, 3 - restart the map, 4 - go to the next map in the map cycle, 5 - spew all edicts.
sv_lowedict_threshold                    : 8        :                  : When only this many edicts are free, take the action specified by sv_lowedict_action.
sv_massreport                            : 0        : , "sv"           :
sv_master_share_game_socket              : 1        :                  : Use the game's socket to communicate to the master server. If this is 0, then it will create a socket on -steamport + 1 to communicate to the master server on.
sv_max_connects_sec                      : 2        :                  : Maximum connections per second to respond to from a single IP address.
sv_max_connects_sec_global               : 0        :                  : Maximum connections per second to respond to from anywhere.
sv_max_connects_window                   : 4        :                  : Window over which to average connections per second averages.
sv_max_queries_sec                       : 3        :                  : Maximum queries per second to respond to from a single IP address.
sv_max_queries_sec_global                : 3000     :                  : Maximum queries per second to respond to from anywhere.
sv_max_queries_window                    : 30       :                  : Window over which to average queries per second averages.
sv_max_usercmd_future_ticks              : 8        : , "sv"           : Prevents clients from running usercmds too far in the future. Prevents speed hacks.
sv_maxcmdrate                            : 66       : , "rep"          : (If sv_mincmdrate is > 0), this sets the maximum value for cl_cmdrate.
sv_maxrate                               : 0        : , "rep"          : Max bandwidth rate allowed on server, 0 == unlimited
sv_maxreplay                             : 0        :                  : Maximum replay time in seconds
sv_maxroutable                           : 1260     :                  : Server upper bound on net_maxroutable that a client can use.
sv_maxspeed                              : 320      : , "sv", "nf", "rep" :
sv_maxupdaterate                         : 66       : , "rep"          : Maximum updates per second that the server will allow
sv_maxuptimelimit                        : 0        :                  : If set, whenever a game ends, if the server uptime exceeds this number of hours, the server will exit.
sv_maxusrcmdprocessticks                 : 24       : , "sv", "nf"     : Maximum number of client-issued usrcmd ticks that can be replayed in packet loss conditions, 0 to allow no restrictions
sv_maxusrcmdprocessticks_holdaim         : 1        : , "sv", "cheat"  : Hold client aim for multiple server sim ticks when client-issued usrcmd contains multiple actions (0: off; 1: hold this server tick; 2+: hold multiple ticks)
sv_maxusrcmdprocessticks_warning         : -1       : , "sv"           : Print a warning when user commands get dropped due to insufficient usrcmd ticks allocated, number of seconds to throttle, negative disabled
sv_maxvelocity                           : 3500     : , "sv", "rep"    : Maximum speed any ballistically moving object is allowed to attain per axis.
sv_memlimit                              : 0        :                  : If set, whenever a game ends, if the total memory used by the server is greater than this # of megabytes, the server will exit.
sv_mincmdrate                            : 10       : , "rep"          : This sets the minimum value for cl_cmdrate. 0 == unlimited.
sv_minrate                               : 3500     : , "rep"          : Min bandwidth rate allowed on server, 0 == unlimited
sv_minupdaterate                         : 10       : , "rep"          : Minimum updates per second that the server will allow
sv_minuptimelimit                        : 0        :                  : If set, whenever a game ends, if the server uptime is less than this number of hours, the server will continue running regardless of sv_memlimit.
sv_motd_unload_on_dismissal              : 0        : , "sv"           : If enabled, the MOTD contents will be unloaded when the player closes the MOTD.
sv_namechange_cooldown_seconds           : 30       :                  : When a client name change is received, wait N seconds before allowing another name change
sv_netspike                              : cmd      :                  : Write network trace if amount of data sent to client exceeds N bytes.  Use zero to disable tracing. Note that having this enabled, even if never triggered, impacts performance.  Set to zero when not in use. For compatibility reasons, this command can be initialized on the command line with the -netspike option.
sv_netspike_on_reliable_snapshot_overflow : 0        :                  : If nonzero, the server will dump a netspike trace if a client is dropped due to reliable snapshot overflow
sv_netspike_output                       : 1        :                  : Where the netspike data be written?  Sum of the following values: 1=netspike.txt, 2=ordinary server log
sv_netspike_sendtime_ms                  : 0        :                  : If nonzero, the server will dump a netspike trace if it takes more than N ms to prepare a snapshot to a single client.  This feature does take some CPU cycles, so it should be left off when not in use.
sv_noclipaccelerate                      : 5        : , "a", "sv", "nf", "rep" :
sv_noclipduringpause                     : 0        : , "sv", "cheat", "rep" : If cheats are enabled, then you can noclip with the game paused (for doing screenshots, etc.).
sv_noclipspeed                           : 5        : , "a", "sv", "nf", "rep" :
sv_nomvp                                 : 0        : , "sv"           : Disable MVP awards.
sv_nonemesis                             : 0        : , "sv"           : Disable nemesis and revenge.
sv_noroundstats                          : 1        : , "sv", "rep"    : A temporary variable that can be used for disabling upload of round stats.
sv_nostats                               : 0        : , "sv", "nf", "rep" : Disable collecting statistics and awarding achievements.
sv_nowinpanel                            : 0        : , "sv", "rep"    : Turn on/off win panel on server
sv_npc_talker_maxdist                    : 1024     : , "sv"           : NPCs over this distance from the player won't attempt to speak.
sv_parallel_packentities                 : 1        :                  :
sv_parallel_sendsnapshot                 : 0        :                  :
sv_password                              : 0        : , "nf", "prot", "norecord" : Server password for entry into multiplayer games
sv_pausable                              : 0        : , "nf"           : Is the server pausable.
sv_player_display_usercommand_errors     : 0        : , "sv", "cheat"  : 1 = Display warning when command values are out-of-range. 2 = Spew invalid ranges.
sv_playerperfhistorycount                : 60       : , "sv"           : Number of samples to maintain in player perf history
sv_precacheinfo                          : cmd      :                  : Show precache info.
sv_pure                                  : cmd      :                  : Show user data.
sv_pure_consensus                        : 5        :                  : Minimum number of file hashes to agree to form a consensus.
sv_pure_kick_clients                     : 1        :                  : If set to 1, the server will kick clients with mismatching files. Otherwise, it will issue a warning to the client.
sv_pure_retiretime                       : 900      :                  : Seconds of server idle time to flush the sv_pure file hash cache.
sv_pure_trace                            : 0        :                  : If set to 1, the server will print a message whenever a client is verifying a CRC for a file.
sv_pushaway_clientside                   : 0        : , "sv", "rep"    : Clientside physics push away (0=off, 1=only localplayer, 1=all players)
sv_pushaway_force                        : 30000    : , "sv", "rep"    : How hard physics objects are pushed away from the players on the server.
sv_pushaway_hostage_force                : 20000    : , "sv", "cheat", "rep" : How hard the hostage is pushed away from physics objects (falls off with inverse square of distance).
sv_pushaway_max_force                    : 1000     : , "sv", "rep"    : Maximum amount of force applied to physics objects by players.
sv_pushaway_max_hostage_force            : 1000     : , "sv", "cheat", "rep" : Maximum of how hard the hostage is pushed away from physics objects.
sv_pushaway_max_player_force             : 10000    : , "sv", "cheat", "rep" : Maximum of how hard the player is pushed away from physics objects.
sv_pushaway_min_player_speed             : 75       : , "sv", "rep"    : If a player is moving slower than this, don't push away physics objects (enables ducking behind things).
sv_pushaway_player_force                 : 200000   : , "sv", "cheat", "rep" : How hard the player is pushed away from physics objects (falls off with inverse square of distance).
sv_pvsskipanimation                      : 1        : , "a", "sv"      : Skips SetupBones when npc's are outside the PVS
sv_querycache_stats                      : cmd      :                  : Display status of the query cache (client only)
sv_rcon_banpenalty                       : 0        :                  : Number of minutes to ban users who fail rcon authentication
sv_rcon_log                              : 1        :                  : Enable/disable rcon logging.
sv_rcon_maxfailures                      : 10       :                  : Max number of times a user can fail rcon authentication before being banned
sv_rcon_maxpacketbans                    : 1        :                  : Ban IPs for sending RCON packets exceeding the value specified in sv_rcon_maxpacketsize
sv_rcon_maxpacketsize                    : 1024     :                  : The maximum number of bytes to allow in a command packet
sv_rcon_minfailures                      : 5        :                  : Number of times a user can fail rcon authentication in sv_rcon_minfailuretime before being banned
sv_rcon_minfailuretime                   : 30       :                  : Number of seconds to track failed rcon authentications
sv_rcon_whitelist_address                : 0        :                  : When set, rcon failed authentications will never ban this address, e.g. '127.0.0.1'
sv_region                                : 255      :                  : The region of the world to report this server in.
sv_restrict_aspect_ratio_fov             : 1        : , "rep"          : This can be used to limit the effective FOV of users using wide-screen resolutions with aspect ratios wider than 1.85:1 (slightly wider than 16:9).     0 = do not cap effective FOV     1 = limit the effective FOV on windowed mode users using resolutions         greater than 1.85:1     2 = limit the effective FOV on both windowed mode and full-screen users
sv_rollangle                             : 0        : , "sv", "nf", "rep" : Max view roll angle
sv_rollspeed                             : 200      : , "sv", "nf", "rep" :
sv_runcmds                               : 1        : , "sv"           :
sv_setsteamaccount                       : cmd      :                  : token Set game server account token to use for logging in to a persistent game server account
sv_showimpacts                           : 0        : , "sv", "rep"    : Shows client (red) and server (blue) bullet impact point (1=both, 2=client-only, 3=server-only)
sv_showladders                           : 0        : , "sv"           : Show bbox and dismount points for all ladders (must be set before level load.)
sv_showlagcompensation                   : 0        : , "sv", "cheat"  : Show lag compensated hitboxes whenever a player is lag compensated.
sv_showplayerhitboxes                    : 0        : , "sv", "rep"    : Show lag compensated hitboxes for the specified player index whenever a player fires.
sv_shutdown                              : cmd      :                  : Sets the server to shutdown next time it's empty
sv_shutdown_timeout_minutes              : 360      : , "rep"          : If sv_shutdown is pending, wait at most N minutes for server to drain before forcing shutdown.
sv_skyname                               : 0        : , "a", "sv", "rep" : Current name of the skybox texture
sv_soundemitter_trace                    : 0        : , "sv", "rep"    : Show all EmitSound calls including their symbolic name and the actual wave file they resolved to
sv_specaccelerate                        : 5        : , "a", "sv", "nf", "rep" :
sv_specnoclip                            : 1        : , "a", "sv", "nf", "rep" :
sv_specspeed                             : 3        : , "a", "sv", "nf", "rep" :
sv_stats                                 : 1        :                  : Collect CPU usage stats
sv_steamblockingcheck                    : 0        :                  : Check each new player for Steam blocking compatibility, 1 = message only, 2 >= drop if any member of owning clan blocks,3 >= drop if any player has blocked, 4 >= drop if player has blocked anyone on server
sv_steamgroup                            : 0        : , "nf"           : The ID of the steam group that this server belongs to. You can find your group's ID on the admin profile page in the steam community.
sv_stepsize                              : 18       : , "sv", "nf", "rep" :
sv_stopspeed                             : 75       : , "sv", "nf", "rep" : Minimum stopping speed when on ground.
sv_strict_notarget                       : 0        : , "sv"           : If set, notarget will cause entities to never think they are in the pvs
sv_tags                                  : 0        : , "nf"           : Server tags. Used to provide extra information to clients when they're browsing for servers. Separate tags with a comma.
sv_test_scripted_sequences               : 0        : , "sv"           : Tests for scripted sequences that are embedded in the world. Run through your map with this set to check for NPCs falling through the world.
sv_teststepsimulation                    : 1        : , "sv"           :
sv_thinktimecheck                        : 0        : , "sv"           : Check for thinktimes all on same timestamp.
sv_timebetweenducks                      : 0        : , "sv", "rep"    : Minimum time before recognizing consecutive duck key
sv_timeout                               : 65       :                  : After this many seconds without a message from a client, the client is dropped
sv_turbophysics                          : 0        : , "sv", "rep"    : Turns on turbo physics
sv_unlockedchapters                      : 1        : , "a"            : Highest unlocked game chapter.
sv_usercmd_custom_random_seed            : 1        : , "sv", "cheat"  : When enabled server will populate an additional random seed independent of the client
sv_vehicle_autoaim_scale                 : 8        : , "sv"           :
sv_visiblemaxplayers                     : -1       :                  : Overrides the max players reported to prospective clients
sv_voicecodec                            : 0        :                  : Specifies which voice codec to use. Valid options are: vaudio_speex - Legacy Speex codec (lowest quality) vaudio_celt - Newer CELT codec steam - Use Steam voice API
sv_voiceenable                           : 1        : , "a", "nf"      :
sv_vote_allow_spectators                 : 0        : , "sv"           : Allow spectators to vote?
sv_vote_creation_timer                   : 150      : , "sv"           : How long before a player can attempt to call another vote (in seconds).
sv_vote_failure_timer                    : 300      : , "sv"           : A vote that fails cannot be re-submitted for this long
sv_vote_quorum_ratio                     : 0        : , "sv", "nf"     : The minimum ratio of eligible players needed to pass a vote.  Min 0.5, Max 1.0.
sv_vote_ui_hide_disabled_issues          : 1        : , "sv"           : Suppress listing of disabled issues in the vote setup screen.
sv_wateraccelerate                       : 10       : , "sv", "nf", "rep" :
sv_waterdist                             : 12       : , "sv", "rep"    : Vertical view fixup when eyes are near water plane.
sv_waterfriction                         : 1        : , "sv", "nf", "rep" :
sys_minidumpexpandedspew                 : 1        :                  :
sys_minidumpspewlines                    : 500      :                  : Lines of crash dump console spew to keep.
systemlinkport                           : 27030    :                  : System Link port
telemetry_demoend                        : 0        :                  : When playing demo, stop telemetry on tick #
telemetry_demostart                      : 0        :                  : When playing demo, start telemetry on tick #
telemetry_framecount                     : 0        :                  : Set Telemetry count of frames to capture
telemetry_level                          : 0        :                  : Set Telemetry profile level: 0 being off.
telemetry_pause                          : 0        :                  : Pause Telemetry
telemetry_resume                         : 0        :                  : Resume Telemetry
telemetry_server                         : 0        :                  : Set Telemetry server
template_debug                           : 0        : , "sv"           :
Test_CreateEntity                        : cmd      :                  :
test_dispatcheffect                      : cmd      :                  : Test a clientside dispatch effect.  Usage: test_dispatcheffect <effect name> <distance away> <flags> <magnitude> <scale>  Defaults are: <distance 1024> <flags 0> <magnitude 0> <scale 0>
Test_EHandle                             : cmd      :                  :
test_entity_blocker                      : cmd      :                  : Test command that drops an entity blocker out in front of the player.
Test_InitRandomEntitySpawner             : cmd      :                  :
Test_ProxyToggle_EnableProxy             : cmd      :                  :
Test_ProxyToggle_SetValue                : cmd      :                  :
Test_RandomizeInPVS                      : cmd      :                  :
Test_RandomPlayerPosition                : cmd      :                  :
Test_RemoveAllRandomEntities             : cmd      :                  :
Test_SpawnRandomEntities                 : cmd      :                  :
testscript_debug                         : 0        :                  : Debug test scripts.
texture_budget_background_alpha          : 128      : , "a"            : how translucent the budget panel is
texture_budget_panel_bottom_of_history_fraction : 0        : , "a"            : number between 0 and 1
texture_budget_panel_global              : 0        :                  : Show global times in the texture budget panel.
texture_budget_panel_height              : 284      : , "a"            : height in pixels of the budget panel
texture_budget_panel_width               : 512      : , "a"            : width in pixels of the budget panel
texture_budget_panel_x                   : 0        : , "a"            : number of pixels from the left side of the game screen to draw the budget panel
texture_budget_panel_y                   : 450      : , "a"            : number of pixels from the top side of the game screen to draw the budget panel
tf_arena_max_streak                      : 3        : , "sv", "nf", "rep" : Teams will be scrambled if one team reaches this streak
tf_arena_preround_time                   : 10       : , "sv", "nf", "rep" : Length of the Pre-Round time
tf_arena_round_time                      : 0        : , "sv", "nf", "rep" :
tf_arena_use_queue                       : 1        : , "sv", "nf", "rep" : Enables the spectator queue system for Arena.
tf_escort_score_rate                     : 1        : , "sv", "cheat"  : Score for escorting the train, in points per second
think_limit                              : 0        : , "sv", "rep"    : Maximum think time in milliseconds, warning is printed if this is exceeded.
threadpool_affinity                      : 1        :                  : Enable setting affinity
timedemo                                 : cmd      :                  : Play a demo and report performance info.
timedemo_runcount                        : 0        :                  : Runs time demo X number of times.
timedemoquit                             : cmd      :                  : Play a demo, report performance info, and then exit
timeleft                                 : cmd      :                  : prints the time remaining in the match
timerefresh                              : cmd      :                  : Profile the renderer.
toggle                                   : cmd      :                  : Toggles a convar on or off, or cycles through a set of values.
toggleconsole                            : cmd      :                  : Show/hide the console.
trace_report                             : 0        : , "sv"           :
tv_allow_camera_man                      : 1        : , "sv"           : Auto director allows spectators to become camera man
tv_allow_static_shots                    : 1        : , "sv"           : Auto director uses fixed level cameras for shots
tv_autorecord                            : 0        :                  : Automatically records all games as SourceTV demos.
tv_autoretry                             : 1        :                  : Relay proxies retry connection after network timeout
tv_chatgroupsize                         : 0        :                  : Set the default chat group size
tv_chattimelimit                         : 8        :                  : Limits spectators to chat only every n seconds
tv_clients                               : cmd      :                  : Shows list of connected SourceTV clients.
tv_debug                                 : 0        :                  : SourceTV debug info.
tv_delay                                 : 30       : , "sv"           : SourceTV broadcast delay in seconds
tv_delaymapchange                        : 0        : , "sv"           : Delays map change until broadcast is complete
tv_delaymapchange_protect                : 1        : , "sv"           : Protect against doing a manual map change if HLTV is broadcasting and has not caught up with a major game event such as round_end
tv_deltacache                            : 2        :                  : Enable delta entity bit stream cache
tv_dispatchmode                          : 1        :                  : Dispatch clients to relay proxies: 0=never, 1=if appropriate, 2=always
tv_enable                                : 0        : , "nf"           : Activates SourceTV on server.
tv_maxclients                            : 128      :                  : Maximum client number on SourceTV server.
tv_maxrate                               : 8000     :                  : Max SourceTV spectator bandwidth rate allowed, 0 == unlimited
tv_msg                                   : cmd      :                  : Send a screen message to all clients.
tv_name                                  : 0        :                  : SourceTV host name
tv_nochat                                : 0        : , "a", "user"    : Don't receive chat messages from other SourceTV spectators
tv_overridemaster                        : 0        :                  : Overrides the SourceTV master root address.
tv_password                              : 0        : , "nf", "prot", "norecord" : SourceTV password for all clients
tv_port                                  : 27020    :                  : Host SourceTV port
tv_record                                : cmd      :                  : Starts SourceTV demo recording.
tv_relay                                 : cmd      :                  : Connect to SourceTV server and relay broadcast.
tv_relaypassword                         : 0        : , "nf", "prot", "norecord" : SourceTV password for relay proxies
tv_relayvoice                            : 1        :                  : Relay voice data: 0=off, 1=on
tv_retry                                 : cmd      :                  : Reconnects the SourceTV relay proxy.
tv_snapshotrate                          : 16       :                  : Snapshots broadcasted per second
tv_status                                : cmd      :                  : Show SourceTV server status.
tv_stop                                  : cmd      :                  : Stops the SourceTV broadcast.
tv_stoprecord                            : cmd      :                  : Stops SourceTV demo recording.
tv_timeout                               : 30       :                  : SourceTV connection timeout in seconds.
tv_title                                 : 0        :                  : Set title for SourceTV spectator UI
tv_transmitall                           : 0        : , "rep"          : Transmit all entities (not only director view)
unbind                                   : cmd      :                  : Unbind a key.
unbind_mac                               : cmd      :                  : Unbind a key on the Mac only.
unbindall                                : cmd      :                  : Unbind all keys.
unpause                                  : cmd      :                  : Unpause the game.
use                                      : cmd      :                  : Use a particular weapon  Arguments: <weapon_name>
user                                     : cmd      :                  : Show user data.
users                                    : cmd      :                  : Show user info for players on server.
vcr_verbose                              : 0        :                  : Write extra information into .vcr file.
vehicle_flushscript                      : cmd      :                  : Flush and reload all vehicle scripts
version                                  : cmd      :                  : Print version info string.
vgui_drawfocus                           : 0        :                  : Report which panel is under the mouse.
vgui_drawtree                            : 0        : , "cheat"        : Draws the vgui panel hiearchy to the specified depth level.
+vgui_drawtree                           : cmd      :                  :
-vgui_drawtree                           : cmd      :                  :
vgui_drawtree_bounds                     : 0        :                  : Show panel bounds.
vgui_drawtree_clear                      : cmd      :                  :
vgui_drawtree_draw_selected              : 0        :                  : Highlight the selected panel
vgui_drawtree_freeze                     : 0        :                  : Set to 1 to stop updating the vgui_drawtree view.
vgui_drawtree_hidden                     : 0        :                  : Draw the hidden panels.
vgui_drawtree_panelalpha                 : 0        :                  : Show the panel alpha values in the vgui_drawtree view.
vgui_drawtree_panelptr                   : 0        :                  : Show the panel pointer values in the vgui_drawtree view.
vgui_drawtree_popupsonly                 : 0        :                  : Draws the vgui popup list in hierarchy(1) or most recently used(2) order.
vgui_drawtree_render_order               : 0        :                  : List the vgui_drawtree panels in render order.
vgui_drawtree_visible                    : 1        :                  : Draw the visible panels.
vgui_spew_fonts                          : cmd      :                  :
vgui_togglepanel                         : cmd      :                  : show/hide vgui panel by name.
violence_ablood                          : 1        :                  : Draw alien blood
violence_agibs                           : 1        :                  : Show alien gib entities
violence_hblood                          : 1        :                  : Draw human blood
violence_hgibs                           : 1        :                  : Show human gib entities
voice_avggain                            : 0        :                  :
voice_buffer_ms                          : 100      :                  : How many milliseconds of voice to buffer to avoid dropouts due to jitter and frame time differences.
voice_debugfeedback                      : 0        :                  :
voice_debugfeedbackfrom                  : 0        :                  :
voice_enable                             : 1        : , "a"            :
voice_fadeouttime                        : 0        :                  :
voice_forcemicrecord                     : 1        : , "a"            :
voice_inputfromfile                      : 0        :                  : Get voice input from 'voice_input.wav' rather than from the microphone.
voice_loopback                           : 0        : , "user"         :
voice_maxgain                            : 10       :                  :
voice_overdrive                          : 2        :                  :
voice_overdrivefadetime                  : 0        :                  :
voice_printtalkers                       : cmd      :                  : voice debug.
voice_profile                            : 0        :                  :
voice_recordtofile                       : 0        :                  : Record mic data and decompressed voice data into 'voice_micdata.wav' and 'voice_decompressed.wav'
voice_scale                              : 1        : , "a"            :
voice_serverdebug                        : 0        : , "sv"           :
voice_showchannels                       : 0        :                  :
voice_showincoming                       : 0        :                  :
voice_steal                              : 2        :                  :
voice_writevoices                        : 0        :                  : Saves each speaker's voice data into separate .wav files
+voicerecord                             : cmd      :                  :
-voicerecord                             : cmd      :                  :
volume                                   : 1        : , "a"            : Sound volume
vox_reload                               : cmd      :                  : Reload sentences.txt file
voxeltree_box                            : cmd      :                  : View entities in the voxel-tree inside box <Vector(min), Vector(max)>.
voxeltree_playerview                     : cmd      :                  : View entities in the voxel-tree at the player position.
voxeltree_sphere                         : cmd      :                  : View entities in the voxel-tree inside sphere <Vector(center), float(radius)>.
voxeltree_view                           : cmd      :                  : View entities in the voxel-tree.
vprof                                    : cmd      :                  : Toggle VProf profiler
vprof_adddebuggroup1                     : cmd      :                  : add a new budget group dynamically for debugging
vprof_cachemiss                          : cmd      :                  : Toggle VProf cache miss checking
vprof_cachemiss_off                      : cmd      :                  : Turn off VProf cache miss checking
vprof_cachemiss_on                       : cmd      :                  : Turn on VProf cache miss checking
vprof_child                              : cmd      :                  :
vprof_collapse_all                       : cmd      :                  : Collapse the whole vprof tree
vprof_counters                           : 0        :                  :
vprof_dump_groupnames                    : cmd      :                  : Write the names of all of the vprof groups to the console.
vprof_dump_oninterval                    : 0        :                  : Interval (in seconds) at which vprof will batch up data and dump it to the console.
vprof_dump_spikes                        : 0        :                  : Framerate at which vprof will begin to dump spikes to the console. 0 = disabled, negative to reset after dump
vprof_dump_spikes_budget_group           : 0        :                  : Budget gtNode to start report from when doing a dump spikes
vprof_dump_spikes_node                   : 0        :                  : Node to start report from when doing a dump spikes
vprof_expand_all                         : cmd      :                  : Expand the whole vprof tree
vprof_expand_group                       : cmd      :                  : Expand a budget group in the vprof tree by name
vprof_generate_report                    : cmd      :                  : Generate a report to the console.
vprof_generate_report_AI                 : cmd      :                  : Generate a report to the console.
vprof_generate_report_AI_only            : cmd      :                  : Generate a report to the console.
vprof_generate_report_budget             : cmd      :                  : Generate a report to the console based on budget group.
vprof_generate_report_hierarchy          : cmd      :                  : Generate a report to the console.
vprof_generate_report_map_load           : cmd      :                  : Generate a report to the console.
vprof_graph                              : 0        :                  : Draw the vprof graph.
vprof_graphheight                        : 256      : , "a"            :
vprof_graphwidth                         : 512      : , "a"            :
vprof_nextsibling                        : cmd      :                  :
vprof_off                                : cmd      :                  : Turn off VProf profiler
vprof_on                                 : cmd      :                  : Turn on VProf profiler
vprof_parent                             : cmd      :                  :
vprof_playback_average                   : cmd      :                  : Average the next N frames.
vprof_playback_start                     : cmd      :                  : Start playing back a recorded .vprof file.
vprof_playback_step                      : cmd      :                  : While playing back a .vprof file, step to the next tick.
vprof_playback_stepback                  : cmd      :                  : While playing back a .vprof file, step to the previous tick.
vprof_playback_stop                      : cmd      :                  : Stop playing back a recorded .vprof file.
vprof_prevsibling                        : cmd      :                  :
vprof_record_start                       : cmd      :                  : Start recording vprof data for playback later.
vprof_record_stop                        : cmd      :                  : Stop recording vprof data
vprof_remote_start                       : cmd      :                  : Request a VProf data stream from the remote server (requires authentication)
vprof_remote_stop                        : cmd      :                  : Stop an existing remote VProf data request
vprof_report_oninterval                  : 0        :                  : Interval (in seconds) at which vprof will batch up a full report to the console -- more detailed than vprof_dump_oninterval.
vprof_reset                              : cmd      :                  : Reset the stats in VProf profiler
vprof_reset_peaks                        : cmd      :                  : Reset just the peak time in VProf profiler
vprof_scope                              : 0        :                  : Set a specific scope to start showing vprof tree
vprof_scope_entity_gamephys              : 0        : , "sv"           :
vprof_scope_entity_thinks                : 0        : , "sv"           :
vprof_unaccounted_limit                  : 0        : , "a"            : number of milliseconds that a node must exceed to turn red in the vprof panel
vprof_verbose                            : 1        : , "a"            : Set to one to show average and peak times
vprof_vtrace                             : cmd      :                  : Toggle whether vprof data is sent to VTrace
vprof_vtune_group                        : cmd      :                  : enable vtune for a particular vprof group ('disable' to disable)
vprof_warningmsec                        : 10       : , "a"            : Above this many milliseconds render the label red to indicate slow code.
vtune                                    : cmd      :                  : Controls VTune's sampling.
wc_air_edit_further                      : cmd      :                  : When in WC edit mode and editing air nodes,  moves position of air node crosshair and placement location further away from player
wc_air_edit_nearer                       : cmd      :                  : When in WC edit mode and editing air nodes,  moves position of air node crosshair and placement location nearer to from player
wc_air_node_edit                         : cmd      :                  : When in WC edit mode, toggles laying down or air nodes instead of ground nodes
wc_create                                : cmd      :                  : When in WC edit mode, creates a node where the player is looking if a node is allowed at that location for the currently selected hull size (see ai_next_hull)
wc_destroy                               : cmd      :                  : When in WC edit mode, destroys the node that the player is nearest to looking at.  (The node will be highlighted by a red box).
wc_destroy_undo                          : cmd      :                  : When in WC edit mode restores the last deleted node
wc_link_edit                             : cmd      :                  :
weapon_showproficiency                   : 0        : , "sv"           :
windows_speaker_config                   : -1       : , "a"            :
wipe_nav_attributes                      : cmd      :                  : Clear all nav attributes of selected area.
writeid                                  : cmd      :                  : Writes a list of permanently-banned user IDs to banned_user.cfg.
writeip                                  : cmd      :                  : Save the ban list to banned_ip.cfg.
xbox_autothrottle                        : 1        : , "a", "sv"      :
xbox_steering_deadzone                   : 0        : , "sv"           :
xbox_throttlebias                        : 100      : , "a", "sv"      :
xbox_throttlespoof                       : 200      : , "a", "sv"      :
xc_crouch_debounce                       : 0        : , "sv"           :
xload                                    : cmd      :                  : Load a saved game from a 360 storage device.
xsave                                    : cmd      :                  : Saves current game to a 360 storage device.
--------------
1838 total convars/concommands