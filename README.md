# Disable windows user with Wazuh active response


Hi, use the code attached above to create an active response to block users on Windows with Wazuh.

  <command>
    <name>disable-account-win</name>
    <executable>disable-account-win.cmd</executable>
    <timeout_allowed>yes</timeout_allowed>
  </command>

  <active-response>
    <command>disable-account-win</command>
    <location>local</location>
    <rules_id>60109</rules_id>
    <timeout>600</timeout>
  </active-response>
