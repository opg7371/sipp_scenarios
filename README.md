# sipp_scenarios
Typical Scenarios of sipp which occur in the field

Scenario Name - uas_v_parameter_missing.xml
Reason - During Normal calls, some of the phones were sending SDP where version field was coming as empty. Thus, SDP was not properly parsed and resulting in a call Failure and service disruption.

Scenario Name - uas_without_sdp.xml
Reason - During Fax call, the caller who will fax to the callee will send the SDP without attaching payload in SDP and hence resulting in a call Failure.

Scenario Name - uas_s_parameter_missing.xml
Reason - During Normal calls, some of the phones were sending SDP where session field was coming as empty. Thus, SDP was not properly parsed and resulting in a call Failure and service disruption.

