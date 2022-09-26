# HANDLE2022

The detailed information will be added after the paper is accepted.

<table width="288" border="0" cellpadding="0" cellspacing="0" style='width:216.00pt;border-collapse:collapse;table-layout:fixed;'>
   <col width="72" span="4" style='width:54.00pt;'/>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl65" height="18" width="72" style='height:13.50pt;width:54.00pt;' x:str><span style='mso-spacerun:yes;'>&nbsp;</span><font class="font1">Features </font><font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl66" width="72" style='width:54.00pt;' x:str>D<font class="font1">escription</font></td>
    <td class="xl65" width="72" style='width:54.00pt;' x:str><span style='mso-spacerun:yes;'>&nbsp;</span><font class="font1">Features </font><font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl66" width="72" style='width:54.00pt;' x:str>D<font class="font1">escription</font></td>
   </tr>
   <tr height="84" style='height:63.00pt;'>
    <td class="xl65" height="84" style='height:63.00pt;' x:str>payload_len_p1 <font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Payload length of first packet with payload</td>
    <td class="xl65" x:str>bwd_iat_tot<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Total time between two packets sent in the backward direction</td>
   </tr>
   <tr height="84" style='height:63.00pt;'>
    <td class="xl65" height="84" style='height:63.00pt;' x:str>payload_len_p2 <font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Payload length of second packet with payload</td>
    <td class="xl65" x:str>bwd_iat_max<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Maximum time between two packets sent in the backward direction</td>
   </tr>
   <tr height="84" style='height:63.00pt;'>
    <td class="xl65" height="84" style='height:63.00pt;' x:str>payload_len_p3 <font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Payload length of third packet with payload</td>
    <td class="xl65" x:str>bwd_iat_min<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Minimum time between two packets sent in the backward direction</td>
   </tr>
   <tr height="84" style='height:63.00pt;'>
    <td class="xl65" height="84" style='height:63.00pt;' x:str>payload_timestamp_p1</td>
    <td class="xl65" x:str>Timestamp of first packet with payload</td>
    <td class="xl65" x:str>bwd_iat_mean<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Mean time between two packets sent in the backward direction</td>
   </tr>
   <tr height="98" style='height:73.50pt;'>
    <td class="xl65" height="98" style='height:73.50pt;' x:str>payload_timestamp_p2</td>
    <td class="xl65" x:str>Timestamp of second packet with payload</td>
    <td class="xl65" x:str>bwd_iat_std<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Standard deviation time between two packets sent in the backward direction</td>
   </tr>
   <tr height="112" style='height:84.00pt;'>
    <td class="xl65" height="112" style='height:84.00pt;' x:str>payload_timestamp_p3</td>
    <td class="xl65" x:str>Timestamp of third packet with payload</td>
    <td class="xl65" x:str>fwd_psh_flags<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Number of times the PSH flag was set in packets travelling in the forward direction (0 for UDP)</td>
   </tr>
   <tr height="112" style='height:84.00pt;'>
    <td class="xl65" height="112" style='height:84.00pt;' x:str>flow_duration<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Duration of the flow in Microsecond</td>
    <td class="xl65" x:str>bwd_psh_flags<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Number of times the PSH flag was set in packets travelling in the backward direction (0 for UDP)</td>
   </tr>
   <tr height="112" style='height:84.00pt;'>
    <td class="xl65" height="112" style='height:84.00pt;' x:str>flow_byts_s<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Number of flow bytes per second</td>
    <td class="xl65" x:str>fwd_urg_flags<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Number of times the URG flag was set in packets travelling in the forward direction (0 for UDP)</td>
   </tr>
   <tr height="112" style='height:84.00pt;'>
    <td class="xl65" height="112" style='height:84.00pt;' x:str>flow_pkts_s<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Number of flow packets per second</td>
    <td class="xl65" x:str>bwd_urg_flags<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Number of times the URG flag was set in packets travelling in the backward direction (0 for UDP)</td>
   </tr>
   <tr height="56" style='height:42.00pt;'>
    <td class="xl65" height="56" style='height:42.00pt;' x:str>fwd_pkts_s<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Number of forward packets per second</td>
    <td class="xl65" x:str>fin_flag_cnt<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Number of packets with FIN</td>
   </tr>
   <tr height="56" style='height:42.00pt;'>
    <td class="xl65" height="56" style='height:42.00pt;' x:str>bwd_pkts_s<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Number of backward packets per second</td>
    <td class="xl65" x:str>syn_flag_cnt<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Number of packets with SYN</td>
   </tr>
   <tr height="42" style='height:31.50pt;'>
    <td class="xl65" height="42" style='height:31.50pt;' x:str>tot_fwd_pkts<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Total packets in the forward direction</td>
    <td class="xl65" x:str>rst_flag_cnt<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Number of packets with RST</td>
   </tr>
   <tr height="56" style='height:42.00pt;'>
    <td class="xl65" height="56" style='height:42.00pt;' x:str>tot_bwd_pkts<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Total packets in the backward direction</td>
    <td class="xl65" x:str>psh_flag_cnt<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Number of packets with PUSH</td>
   </tr>
   <tr height="56" style='height:42.00pt;'>
    <td class="xl65" height="56" style='height:42.00pt;' x:str>totlen_fwd_pkts<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Total size of packet in forward direction</td>
    <td class="xl65" x:str>ack_flag_cnt<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Number of packets with ACK</td>
   </tr>
   <tr height="56" style='height:42.00pt;'>
    <td class="xl65" height="56" style='height:42.00pt;' x:str>totlen_bwd_pkts<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Total size of packet in backward direction</td>
    <td class="xl65" x:str>urg_flag_cnt<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Number of packets with URG</td>
   </tr>
   <tr height="56" style='height:42.00pt;'>
    <td class="xl65" height="56" style='height:42.00pt;' x:str>fwd_pkt_len_max<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Maximum size of packet in forward direction</td>
    <td class="xl65" x:str>cwe_flag_count<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Number of packets with CWR</td>
   </tr>
   <tr height="56" style='height:42.00pt;'>
    <td class="xl65" height="56" style='height:42.00pt;' x:str>fwd_pkt_len_min<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Minimum size of packet in forward direction</td>
    <td class="xl65" x:str>ece_flag_cnt<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Number of packets with ECE</td>
   </tr>
   <tr height="56" style='height:42.00pt;'>
    <td class="xl65" height="56" style='height:42.00pt;' x:str>fwd_pkt_len_mean<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Mean size of packet in forward direction</td>
    <td class="xl65" x:str>down_up_ratio<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Download and upload ratio</td>
   </tr>
   <tr height="70" style='height:52.50pt;'>
    <td class="xl65" height="70" style='height:52.50pt;' x:str>fwd_pkt_len_std<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Standard deviation size of packet in forward direction</td>
    <td class="xl65" x:str>pkt_size_avg<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Average size of packet</td>
   </tr>
   <tr height="84" style='height:63.00pt;'>
    <td class="xl65" height="84" style='height:63.00pt;' x:str>bwd_pkt_len_max<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Maximum size of packet in backward direction</td>
    <td class="xl65" x:str>init_fwd_win_byts<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;</span></font></td>
    <td class="xl65" x:str>The total number of bytes sent in initial window in the forward direction</td>
   </tr>
   <tr height="98" style='height:73.50pt;'>
    <td class="xl65" height="98" style='height:73.50pt;' x:str>bwd_pkt_len_min<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Minimum size of packet in backward direction</td>
    <td class="xl65" x:str>init_bwd_win_byts<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;</span></font></td>
    <td class="xl65" x:str>The total number of bytes sent in initial window in the backward direction</td>
   </tr>
   <tr height="84" style='height:63.00pt;'>
    <td class="xl65" height="84" style='height:63.00pt;' x:str>bwd_pkt_len_mean<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Mean size of packet in backward direction</td>
    <td class="xl65" x:str>active_max<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Maximum time a flow was active before becoming idle</td>
   </tr>
   <tr height="84" style='height:63.00pt;'>
    <td class="xl65" height="84" style='height:63.00pt;' x:str>bwd_pkt_len_std<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Standard deviation size of packet in backward direction</td>
    <td class="xl65" x:str>active_min<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Minimum time a flow was active before becoming idle</td>
   </tr>
   <tr height="70" style='height:52.50pt;'>
    <td class="xl65" height="70" style='height:52.50pt;' x:str>pkt_len_max<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Minimum length of a packet</td>
    <td class="xl65" x:str>active_mean<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Mean time a flow was active before becoming idle</td>
   </tr>
   <tr height="98" style='height:73.50pt;'>
    <td class="xl65" height="98" style='height:73.50pt;' x:str>pkt_len_min<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Maximum length of a packet</td>
    <td class="xl65" x:str>active_std<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Standard deviation time a flow was active before becoming idle</td>
   </tr>
   <tr height="84" style='height:63.00pt;'>
    <td class="xl65" height="84" style='height:63.00pt;' x:str>pkt_len_mean<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Mean length of a packet</td>
    <td class="xl65" x:str>idle_max<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Maximum time a flow was idle before becoming active</td>
   </tr>
   <tr height="84" style='height:63.00pt;'>
    <td class="xl65" height="84" style='height:63.00pt;' x:str>pkt_len_std<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Standard deviation length of a packet</td>
    <td class="xl65" x:str>idle_min<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Minimum time a flow was idle before becoming active</td>
   </tr>
   <tr height="70" style='height:52.50pt;'>
    <td class="xl65" height="70" style='height:52.50pt;' x:str>pkt_len_var<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Variance length of a packet</td>
    <td class="xl65" x:str>idle_mean<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Mean time a flow was idle before becoming active</td>
   </tr>
   <tr height="98" style='height:73.50pt;'>
    <td class="xl65" height="98" style='height:73.50pt;' x:str>fwd_header_len<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Total bytes used for headers in the forward direction</td>
    <td class="xl65" x:str>idle_std<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Standard deviation time a flow was idle before becoming active</td>
   </tr>
   <tr height="70" style='height:52.50pt;'>
    <td class="xl65" height="70" style='height:52.50pt;' x:str>bwd_header_len<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Total bytes used for headers in the backward direction</td>
    <td class="xl65" x:str>fwd_byts_b_avg<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Average number of bytes bulk rate in the forward direction</td>
   </tr>
   <tr height="84" style='height:63.00pt;'>
    <td class="xl65" height="84" style='height:63.00pt;' x:str>fwd_seg_size_min<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Minimum segment size observed in the forward direction</td>
    <td class="xl65" x:str>fwd_pkts_b_avg<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Average number of packets bulk rate in the forward direction</td>
   </tr>
   <tr height="98" style='height:73.50pt;'>
    <td class="xl65" height="98" style='height:73.50pt;' x:str>fwd_act_data_pkts<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;</span></font></td>
    <td class="xl65" x:str>Count of packets with at least 1 byte of TCP data payload in the forward direction</td>
    <td class="xl65" x:str>bwd_byts_b_avg<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Average number of bytes bulk rate in the backward direction</td>
   </tr>
   <tr height="84" style='height:63.00pt;'>
    <td class="xl65" height="84" style='height:63.00pt;' x:str>flow_iat_max<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Maximum time between two packets sent in the flow</td>
    <td class="xl65" x:str>bwd_pkts_b_avg<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Average number of packets bulk rate in the backward direction</td>
   </tr>
   <tr height="70" style='height:52.50pt;'>
    <td class="xl65" height="70" style='height:52.50pt;' x:str>flow_iat_min<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Minimum time between two packets sent in the flow</td>
    <td class="xl65" x:str>fwd_blk_rate_avg<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;</span></font></td>
    <td class="xl65" x:str>Average number of bulk rate in the forward direction</td>
   </tr>
   <tr height="70" style='height:52.50pt;'>
    <td class="xl65" height="70" style='height:52.50pt;' x:str>flow_iat_mean<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Mean time between two packets sent in the flow</td>
    <td class="xl65" x:str>bwd_blk_rate_avg<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;</span></font></td>
    <td class="xl65" x:str>Average number of bulk rate in the backward direction</td>
   </tr>
   <tr height="84" style='height:63.00pt;'>
    <td class="xl65" height="84" style='height:63.00pt;' x:str>flow_iat_std<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Standard deviation time between two packets sent in the flow</td>
    <td class="xl65" x:str>fwd_seg_size_avg<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;</span></font></td>
    <td class="xl65" x:str>Average size observed in the forward direction</td>
   </tr>
   <tr height="70" style='height:52.50pt;'>
    <td class="xl65" height="70" style='height:52.50pt;' x:str>fwd_iat_tot<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Total time between two packets sent in the forward direction</td>
    <td class="xl65" x:str>bwd_seg_size_avg<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;</span></font></td>
    <td class="xl65" x:str>Average size observed in the backward direction</td>
   </tr>
   <tr height="84" style='height:63.00pt;'>
    <td class="xl65" height="84" style='height:63.00pt;' x:str>fwd_iat_max<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Maximum time between two packets sent in the forward direction</td>
    <td class="xl65" x:str>subflow_fwd_pkts<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>The average number of packets in a sub flow in the forward direction</td>
   </tr>
   <tr height="84" style='height:63.00pt;'>
    <td class="xl65" height="84" style='height:63.00pt;' x:str>fwd_iat_min<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Minimum time between two packets sent in the forward direction</td>
    <td class="xl65" x:str>subflow_bwd_pkts<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>The average number of packets in a sub flow in the backward direction</td>
   </tr>
   <tr height="84" style='height:63.00pt;'>
    <td class="xl65" height="84" style='height:63.00pt;' x:str>fwd_iat_mean<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Mean time between two packets sent in the forward direction</td>
    <td class="xl65" x:str>subflow_fwd_byts<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>The average number of bytes in a sub flow in the forward direction</td>
   </tr>
   <tr height="98" style='height:73.50pt;'>
    <td class="xl65" height="98" style='height:73.50pt;' x:str>fwd_iat_std<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>Standard deviation time between two packets sent in the forward direction</td>
    <td class="xl65" x:str>subflow_bwd_byts<font class="font1"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;</span></font></td>
    <td class="xl65" x:str>The average number of bytes in a sub flow in the backward direction</td>
   </tr>
   <![if supportMisalignedColumns]>
    <tr width="0" style='display:none;'/>
   <![endif]>
  </table>
