# Which is a valid method of logging messages to the execution log in APEX automation?

1. [x] apex_debug.info('SAL for ' || :ENAME || ' increased by 1%.');
1. [ ] apex_automation.log_info('SAL for ' || :ENAME || ' increased by 1%.');
1. [ ] apex_error.add_error(p_message => 'SAL for ' || :ENAME || ' increased by 1%.', p_display_location => apex_error.c_inline_in_notification);