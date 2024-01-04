---
title: API Tags
toc: true
menu: API Tags
order: 2
// Autogenerated with 'ejabberdctl gen_markdown_doc_for_tags'
---

This section enumerates the tags and their associated API.


## accounts


* [ban_account](/archive/23_10/admin-api/#ban-account)


* [change_password](/archive/23_10/admin-api/#change-password)


* [check_account](/archive/23_10/admin-api/#check-account)


* [check_password](/archive/23_10/admin-api/#check-password)


* [check_password_hash](/archive/23_10/admin-api/#check-password-hash)


* [delete_old_users](/archive/23_10/admin-api/#delete-old-users)


* [delete_old_users_vhost](/archive/23_10/admin-api/#delete-old-users-vhost)


* [register](/archive/23_10/admin-api/#register)


* [registered_users](/archive/23_10/admin-api/#registered-users)


* [unban_ip](/archive/23_10/admin-api/#unban-ip)


* [unregister](/archive/23_10/admin-api/#unregister)


## acme


* [list_certificates](/archive/23_10/admin-api/#list-certificates)


* [request_certificate](/archive/23_10/admin-api/#request-certificate)


* [revoke_certificate](/archive/23_10/admin-api/#revoke-certificate)


## cluster


* [join_cluster](/archive/23_10/admin-api/#join-cluster)


* [leave_cluster](/archive/23_10/admin-api/#leave-cluster)


* [list_cluster](/archive/23_10/admin-api/#list-cluster)


* [set_master](/archive/23_10/admin-api/#set-master)


## config


* [convert_to_yaml](/archive/23_10/admin-api/#convert-to-yaml)


* [dump_config](/archive/23_10/admin-api/#dump-config)


* [reload_config](/archive/23_10/admin-api/#reload-config)


## documentation


* [gen_html_doc_for_commands](/archive/23_10/admin-api/#gen-html-doc-for-commands)


* [gen_markdown_doc_for_commands](/archive/23_10/admin-api/#gen-markdown-doc-for-commands)


* [gen_markdown_doc_for_tags](/archive/23_10/admin-api/#gen-markdown-doc-for-tags)


* [man](/archive/23_10/admin-api/#man)


## erlang


* [compile](/archive/23_10/admin-api/#compile)


* [get_cookie](/archive/23_10/admin-api/#get-cookie)


* [restart_module](/archive/23_10/admin-api/#restart-module)


## last


* [get_last](/archive/23_10/admin-api/#get-last)


* [set_last](/archive/23_10/admin-api/#set-last)


## logs


* [get_loglevel](/archive/23_10/admin-api/#get-loglevel)


* [reopen_log](/archive/23_10/admin-api/#reopen-log)


* [rotate_log](/archive/23_10/admin-api/#rotate-log)


* [set_loglevel](/archive/23_10/admin-api/#set-loglevel)


## mam


* [remove_mam_for_user](/archive/23_10/admin-api/#remove-mam-for-user)


* [remove_mam_for_user_with_peer](/archive/23_10/admin-api/#remove-mam-for-user-with-peer)


## mnesia


* [backup](/archive/23_10/admin-api/#backup)


* [delete_mnesia](/archive/23_10/admin-api/#delete-mnesia)


* [dump](/archive/23_10/admin-api/#dump)


* [dump_table](/archive/23_10/admin-api/#dump-table)


* [export2sql](/archive/23_10/admin-api/#export2sql)


* [export_piefxis](/archive/23_10/admin-api/#export-piefxis)


* [export_piefxis_host](/archive/23_10/admin-api/#export-piefxis-host)


* [import_dir](/archive/23_10/admin-api/#import-dir)


* [import_file](/archive/23_10/admin-api/#import-file)


* [import_piefxis](/archive/23_10/admin-api/#import-piefxis)


* [import_prosody](/archive/23_10/admin-api/#import-prosody)


* [install_fallback](/archive/23_10/admin-api/#install-fallback)


* [load](/archive/23_10/admin-api/#load)


* [mnesia_change_nodename](/archive/23_10/admin-api/#mnesia-change-nodename)


* [mnesia_info](/archive/23_10/admin-api/#mnesia-info)


* [mnesia_table_info](/archive/23_10/admin-api/#mnesia-table-info)


* [restore](/archive/23_10/admin-api/#restore)


## modules


* [module_check](/archive/23_10/admin-api/#module-check)


* [module_install](/archive/23_10/admin-api/#module-install)


* [module_uninstall](/archive/23_10/admin-api/#module-uninstall)


* [module_upgrade](/archive/23_10/admin-api/#module-upgrade)


* [modules_available](/archive/23_10/admin-api/#modules-available)


* [modules_installed](/archive/23_10/admin-api/#modules-installed)


* [modules_update_specs](/archive/23_10/admin-api/#modules-update-specs)


## muc


* [create_rooms_file](/archive/23_10/admin-api/#create-rooms-file)


* [destroy_rooms_file](/archive/23_10/admin-api/#destroy-rooms-file)


* [get_user_rooms](/archive/23_10/admin-api/#get-user-rooms)


* [get_user_subscriptions](/archive/23_10/admin-api/#get-user-subscriptions)


* [muc_online_rooms](/archive/23_10/admin-api/#muc-online-rooms)


* [muc_online_rooms_by_regex](/archive/23_10/admin-api/#muc-online-rooms-by-regex)


* [muc_register_nick](/archive/23_10/admin-api/#muc-register-nick)


* [muc_unregister_nick](/archive/23_10/admin-api/#muc-unregister-nick)


* [rooms_empty_destroy](/archive/23_10/admin-api/#rooms-empty-destroy)


* [rooms_empty_list](/archive/23_10/admin-api/#rooms-empty-list)


* [rooms_unused_destroy](/archive/23_10/admin-api/#rooms-unused-destroy)


* [rooms_unused_list](/archive/23_10/admin-api/#rooms-unused-list)


## muc_room


* [change_room_option](/archive/23_10/admin-api/#change-room-option)


* [create_room](/archive/23_10/admin-api/#create-room)


* [create_room_with_opts](/archive/23_10/admin-api/#create-room-with-opts)


* [destroy_room](/archive/23_10/admin-api/#destroy-room)


* [get_room_affiliation](/archive/23_10/admin-api/#get-room-affiliation)


* [get_room_affiliations](/archive/23_10/admin-api/#get-room-affiliations)


* [get_room_history](/archive/23_10/admin-api/#get-room-history)


* [get_room_occupants](/archive/23_10/admin-api/#get-room-occupants)


* [get_room_occupants_number](/archive/23_10/admin-api/#get-room-occupants-number)


* [get_room_options](/archive/23_10/admin-api/#get-room-options)


* [get_subscribers](/archive/23_10/admin-api/#get-subscribers)


* [send_direct_invitation](/archive/23_10/admin-api/#send-direct-invitation)


* [set_room_affiliation](/archive/23_10/admin-api/#set-room-affiliation)


* [subscribe_room](/archive/23_10/admin-api/#subscribe-room)


* [subscribe_room_many](/archive/23_10/admin-api/#subscribe-room-many)


* [unsubscribe_room](/archive/23_10/admin-api/#unsubscribe-room)


## oauth


* [oauth_add_client_implicit](/archive/23_10/admin-api/#oauth-add-client-implicit)


* [oauth_add_client_password](/archive/23_10/admin-api/#oauth-add-client-password)


* [oauth_issue_token](/archive/23_10/admin-api/#oauth-issue-token)


* [oauth_list_tokens](/archive/23_10/admin-api/#oauth-list-tokens)


* [oauth_remove_client](/archive/23_10/admin-api/#oauth-remove-client)


* [oauth_revoke_token](/archive/23_10/admin-api/#oauth-revoke-token)


## offline


* [get_offline_count](/archive/23_10/admin-api/#get-offline-count)


## private


* [bookmarks_to_pep](/archive/23_10/admin-api/#bookmarks-to-pep)


* [private_get](/archive/23_10/admin-api/#private-get)


* [private_set](/archive/23_10/admin-api/#private-set)


## purge


* [abort_delete_old_mam_messages](/archive/23_10/admin-api/#abort-delete-old-mam-messages)


* [abort_delete_old_messages](/archive/23_10/admin-api/#abort-delete-old-messages)


* [delete_expired_messages](/archive/23_10/admin-api/#delete-expired-messages)


* [delete_expired_pubsub_items](/archive/23_10/admin-api/#delete-expired-pubsub-items)


* [delete_old_mam_messages](/archive/23_10/admin-api/#delete-old-mam-messages)


* [delete_old_mam_messages_batch](/archive/23_10/admin-api/#delete-old-mam-messages-batch)


* [delete_old_mam_messages_status](/archive/23_10/admin-api/#delete-old-mam-messages-status)


* [delete_old_messages](/archive/23_10/admin-api/#delete-old-messages)


* [delete_old_messages_batch](/archive/23_10/admin-api/#delete-old-messages-batch)


* [delete_old_messages_status](/archive/23_10/admin-api/#delete-old-messages-status)


* [delete_old_pubsub_items](/archive/23_10/admin-api/#delete-old-pubsub-items)


* [delete_old_push_sessions](/archive/23_10/admin-api/#delete-old-push-sessions)


* [delete_old_users](/archive/23_10/admin-api/#delete-old-users)


* [delete_old_users_vhost](/archive/23_10/admin-api/#delete-old-users-vhost)


## roster


* [add_rosteritem](/archive/23_10/admin-api/#add-rosteritem)


* [delete_rosteritem](/archive/23_10/admin-api/#delete-rosteritem)


* [get_roster](/archive/23_10/admin-api/#get-roster)


* [process_rosteritems](/archive/23_10/admin-api/#process-rosteritems)


* [push_alltoall](/archive/23_10/admin-api/#push-alltoall)


* [push_roster](/archive/23_10/admin-api/#push-roster)


* [push_roster_all](/archive/23_10/admin-api/#push-roster-all)


## s2s


* [incoming_s2s_number](/archive/23_10/admin-api/#incoming-s2s-number)


* [outgoing_s2s_number](/archive/23_10/admin-api/#outgoing-s2s-number)


* [stop_s2s_connections](/archive/23_10/admin-api/#stop-s2s-connections)


## server


* [clear_cache](/archive/23_10/admin-api/#clear-cache)


* [gc](/archive/23_10/admin-api/#gc)


* [halt](/archive/23_10/admin-api/#halt)


* [registered_vhosts](/archive/23_10/admin-api/#registered-vhosts)


* [restart](/archive/23_10/admin-api/#restart)


* [status](/archive/23_10/admin-api/#status)


* [stop](/archive/23_10/admin-api/#stop)


* [stop_kindly](/archive/23_10/admin-api/#stop-kindly)


* [update](/archive/23_10/admin-api/#update)


* [update_list](/archive/23_10/admin-api/#update-list)


## session


* [connected_users](/archive/23_10/admin-api/#connected-users)


* [connected_users_info](/archive/23_10/admin-api/#connected-users-info)


* [connected_users_number](/archive/23_10/admin-api/#connected-users-number)


* [connected_users_vhost](/archive/23_10/admin-api/#connected-users-vhost)


* [get_presence](/archive/23_10/admin-api/#get-presence)


* [kick_session](/archive/23_10/admin-api/#kick-session)


* [kick_user](/archive/23_10/admin-api/#kick-user)


* [num_resources](/archive/23_10/admin-api/#num-resources)


* [resource_num](/archive/23_10/admin-api/#resource-num)


* [set_presence](/archive/23_10/admin-api/#set-presence)


* [status_list](/archive/23_10/admin-api/#status-list)


* [status_list_host](/archive/23_10/admin-api/#status-list-host)


* [status_num](/archive/23_10/admin-api/#status-num)


* [status_num_host](/archive/23_10/admin-api/#status-num-host)


* [user_resources](/archive/23_10/admin-api/#user-resources)


* [user_sessions_info](/archive/23_10/admin-api/#user-sessions-info)


## shared_roster_group


* [srg_create](/archive/23_10/admin-api/#srg-create)


* [srg_delete](/archive/23_10/admin-api/#srg-delete)


* [srg_get_info](/archive/23_10/admin-api/#srg-get-info)


* [srg_get_members](/archive/23_10/admin-api/#srg-get-members)


* [srg_list](/archive/23_10/admin-api/#srg-list)


* [srg_user_add](/archive/23_10/admin-api/#srg-user-add)


* [srg_user_del](/archive/23_10/admin-api/#srg-user-del)


## sql


* [convert_to_scram](/archive/23_10/admin-api/#convert-to-scram)


* [import_prosody](/archive/23_10/admin-api/#import-prosody)


## stanza


* [privacy_set](/archive/23_10/admin-api/#privacy-set)


* [send_message](/archive/23_10/admin-api/#send-message)


* [send_stanza](/archive/23_10/admin-api/#send-stanza)


* [send_stanza_c2s](/archive/23_10/admin-api/#send-stanza-c2s)


## statistics


* [connected_users_number](/archive/23_10/admin-api/#connected-users-number)


* [incoming_s2s_number](/archive/23_10/admin-api/#incoming-s2s-number)


* [outgoing_s2s_number](/archive/23_10/admin-api/#outgoing-s2s-number)


* [stats](/archive/23_10/admin-api/#stats)


* [stats_host](/archive/23_10/admin-api/#stats-host)


* [status_num](/archive/23_10/admin-api/#status-num)


* [status_num_host](/archive/23_10/admin-api/#status-num-host)


## vcard


* [get_vcard](/archive/23_10/admin-api/#get-vcard)


* [get_vcard2](/archive/23_10/admin-api/#get-vcard2)


* [get_vcard2_multi](/archive/23_10/admin-api/#get-vcard2-multi)


* [set_nickname](/archive/23_10/admin-api/#set-nickname)


* [set_vcard](/archive/23_10/admin-api/#set-vcard)


* [set_vcard2](/archive/23_10/admin-api/#set-vcard2)


* [set_vcard2_multi](/archive/23_10/admin-api/#set-vcard2-multi)