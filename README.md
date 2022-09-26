# HANDLE2022

The number of extracted features is 82, and the specific features are indicated as Table.

<table width="1702" border="0" cellpadding="0" cellspacing="0" style='width:1276.50pt;border-collapse:collapse;table-layout:fixed;'>
   <col width="72" class="xl65" style='mso-width-source:userset;mso-width-alt:2304;'/>
   <col width="137" class="xl65" style='mso-width-source:userset;mso-width-alt:4384;'/>
   <col width="482" class="xl65" style='mso-width-source:userset;mso-width-alt:15424;'/>
   <col width="72" class="xl65" style='mso-width-source:userset;mso-width-alt:2304;'/>
   <col width="137" class="xl65" style='mso-width-source:userset;mso-width-alt:4384;'/>
   <col width="802" class="xl65" style='mso-width-source:userset;mso-width-alt:25664;'/>
   <col width="72" span="16378" class="xl65" style='mso-width-source:userset;mso-width-alt:2304;'/>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl66" height="18" width="72" style='height:13.50pt;width:54.00pt;' x:str>No</td>
    <td class="xl67" width="137" style='width:102.75pt;' x:str><span style='mso-spacerun:yes;'>&nbsp;</span>Features<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl68" width="482" style='width:361.50pt;' x:str>Description</td>
    <td class="xl68" width="72" style='width:54.00pt;' x:str>No</td>
    <td class="xl67" width="137" style='width:102.75pt;' x:str><span style='mso-spacerun:yes;'>&nbsp;</span>Features<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl68" width="802" style='width:601.50pt;' x:str>Description</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>1</td>
    <td class="xl67" x:str>payload_len_p1<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Payload length of first packet with payload</td>
    <td class="xl70" x:num>42</td>
    <td class="xl67" x:str>bwd_iat_tot<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Total time between two packets sent in the backward direction</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>2</td>
    <td class="xl67" x:str>payload_len_p2<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Payload length of second packet with payload</td>
    <td class="xl70" x:num>43</td>
    <td class="xl67" x:str>bwd_iat_max<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Maximum time between two packets sent in the backward direction</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>3</td>
    <td class="xl67" x:str>payload_len_p3<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Payload length of third packet with payload</td>
    <td class="xl70" x:num>44</td>
    <td class="xl67" x:str>bwd_iat_min<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Minimum time between two packets sent in the backward direction</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>4</td>
    <td class="xl67" x:str>payload_timestamp_p1</td>
    <td class="xl67" x:str>Timestamp of first packet with payload</td>
    <td class="xl70" x:num>45</td>
    <td class="xl67" x:str>bwd_iat_mean<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Mean time between two packets sent in the backward direction</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>5</td>
    <td class="xl67" x:str>payload_timestamp_p2</td>
    <td class="xl67" x:str>Timestamp of second packet with payload</td>
    <td class="xl70" x:num>46</td>
    <td class="xl67" x:str>bwd_iat_std<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Standard deviation time between two packets sent in the backward direction</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>6</td>
    <td class="xl67" x:str>payload_timestamp_p3</td>
    <td class="xl67" x:str>Timestamp of third packet with payload</td>
    <td class="xl70" x:num>47</td>
    <td class="xl67" x:str>fwd_psh_flags<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Number of times the PSH flag was set in packets travelling in the forward direction (0 for UDP)</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>7</td>
    <td class="xl67" x:str>flow_duration<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Duration of the flow in Microsecond</td>
    <td class="xl70" x:num>48</td>
    <td class="xl67" x:str>bwd_psh_flags<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Number of times the PSH flag was set in packets travelling in the backward direction (0 for UDP)</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>8</td>
    <td class="xl67" x:str>flow_byts_s<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Number of flow bytes per second</td>
    <td class="xl70" x:num>49</td>
    <td class="xl67" x:str>fwd_urg_flags<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Number of times the URG flag was set in packets travelling in the forward direction (0 for UDP)</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>9</td>
    <td class="xl67" x:str>flow_pkts_s<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Number of flow packets per second</td>
    <td class="xl70" x:num>50</td>
    <td class="xl67" x:str>bwd_urg_flags<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Number of times the URG flag was set in packets travelling in the backward direction (0 for UDP)</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>10</td>
    <td class="xl67" x:str>fwd_pkts_s<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Number of forward packets per second</td>
    <td class="xl70" x:num>51</td>
    <td class="xl67" x:str>fin_flag_cnt<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Number of packets with FIN</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>11</td>
    <td class="xl67" x:str>bwd_pkts_s<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Number of backward packets per second</td>
    <td class="xl70" x:num>52</td>
    <td class="xl67" x:str>syn_flag_cnt<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Number of packets with SYN</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>12</td>
    <td class="xl67" x:str>tot_fwd_pkts<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Total packets in the forward direction</td>
    <td class="xl70" x:num>53</td>
    <td class="xl67" x:str>rst_flag_cnt<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Number of packets with RST</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>13</td>
    <td class="xl67" x:str>tot_bwd_pkts<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Total packets in the backward direction</td>
    <td class="xl70" x:num>54</td>
    <td class="xl67" x:str>psh_flag_cnt<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Number of packets with PUSH</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>14</td>
    <td class="xl67" x:str>totlen_fwd_pkts<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Total size of packet in forward direction</td>
    <td class="xl70" x:num>55</td>
    <td class="xl67" x:str>ack_flag_cnt<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Number of packets with ACK</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>15</td>
    <td class="xl67" x:str>totlen_bwd_pkts<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Total size of packet in backward direction</td>
    <td class="xl70" x:num>56</td>
    <td class="xl67" x:str>urg_flag_cnt<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Number of packets with URG</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>16</td>
    <td class="xl67" x:str>fwd_pkt_len_max<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Maximum size of packet in forward direction</td>
    <td class="xl70" x:num>57</td>
    <td class="xl67" x:str>cwe_flag_count<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Number of packets with CWR</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>17</td>
    <td class="xl67" x:str>fwd_pkt_len_min<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Minimum size of packet in forward direction</td>
    <td class="xl70" x:num>58</td>
    <td class="xl67" x:str>ece_flag_cnt<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Number of packets with ECE</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>18</td>
    <td class="xl67" x:str>fwd_pkt_len_mean<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Mean size of packet in forward direction</td>
    <td class="xl70" x:num>59</td>
    <td class="xl67" x:str>down_up_ratio<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Download and upload ratio</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>19</td>
    <td class="xl67" x:str>fwd_pkt_len_std<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Standard deviation size of packet in forward direction</td>
    <td class="xl70" x:num>60</td>
    <td class="xl67" x:str>pkt_size_avg<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Average size of packet</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>20</td>
    <td class="xl67" x:str>bwd_pkt_len_max<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Maximum size of packet in backward direction</td>
    <td class="xl70" x:num>61</td>
    <td class="xl67" x:str>init_fwd_win_byts<span style='mso-spacerun:yes;'>&nbsp;</span></td>
    <td class="xl67" x:str>The total number of bytes sent in initial window in the forward direction</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>21</td>
    <td class="xl67" x:str>bwd_pkt_len_min<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Minimum size of packet in backward direction</td>
    <td class="xl70" x:num>62</td>
    <td class="xl67" x:str>init_bwd_win_byts<span style='mso-spacerun:yes;'>&nbsp;</span></td>
    <td class="xl67" x:str>The total number of bytes sent in initial window in the backward direction</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>22</td>
    <td class="xl67" x:str>bwd_pkt_len_mean<span style='mso-spacerun:yes;'>&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Mean size of packet in backward direction</td>
    <td class="xl70" x:num>63</td>
    <td class="xl67" x:str>active_max<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Maximum time a flow was active before becoming idle</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>23</td>
    <td class="xl67" x:str>bwd_pkt_len_std<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Standard deviation size of packet in backward direction</td>
    <td class="xl70" x:num>64</td>
    <td class="xl67" x:str>active_min<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Minimum time a flow was active before becoming idle</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>24</td>
    <td class="xl67" x:str>pkt_len_max<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Minimum length of a packet</td>
    <td class="xl70" x:num>65</td>
    <td class="xl67" x:str>active_mean<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Mean time a flow was active before becoming idle</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>25</td>
    <td class="xl67" x:str>pkt_len_min<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Maximum length of a packet</td>
    <td class="xl70" x:num>66</td>
    <td class="xl67" x:str>active_std<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Standard deviation time a flow was active before becoming idle</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>26</td>
    <td class="xl67" x:str>pkt_len_mean<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Mean length of a packet</td>
    <td class="xl70" x:num>67</td>
    <td class="xl67" x:str>idle_max<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Maximum time a flow was idle before becoming active</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>27</td>
    <td class="xl67" x:str>pkt_len_std<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Standard deviation length of a packet</td>
    <td class="xl70" x:num>68</td>
    <td class="xl67" x:str>idle_min<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Minimum time a flow was idle before becoming active</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>28</td>
    <td class="xl67" x:str>pkt_len_var<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Variance length of a packet</td>
    <td class="xl70" x:num>69</td>
    <td class="xl67" x:str>idle_mean<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Mean time a flow was idle before becoming active</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>29</td>
    <td class="xl67" x:str>fwd_header_len<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Total bytes used for headers in the forward direction</td>
    <td class="xl70" x:num>70</td>
    <td class="xl67" x:str>idle_std<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Standard deviation time a flow was idle before becoming active</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>30</td>
    <td class="xl67" x:str>bwd_header_len<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Total bytes used for headers in the backward direction</td>
    <td class="xl70" x:num>71</td>
    <td class="xl67" x:str>fwd_byts_b_avg<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Average number of bytes bulk rate in the forward direction</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>31</td>
    <td class="xl67" x:str>fwd_seg_size_min<span style='mso-spacerun:yes;'>&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Minimum segment size observed in the forward direction</td>
    <td class="xl70" x:num>72</td>
    <td class="xl67" x:str>fwd_pkts_b_avg<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Average number of packets bulk rate in the forward direction</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>32</td>
    <td class="xl67" x:str>fwd_act_data_pkts<span style='mso-spacerun:yes;'>&nbsp;</span></td>
    <td class="xl67" x:str>Count of packets with at least 1 byte of TCP data payload in the forward direction</td>
    <td class="xl70" x:num>73</td>
    <td class="xl67" x:str>bwd_byts_b_avg<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Average number of bytes bulk rate in the backward direction</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>33</td>
    <td class="xl67" x:str>flow_iat_max<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Maximum time between two packets sent in the flow</td>
    <td class="xl70" x:num>74</td>
    <td class="xl67" x:str>bwd_pkts_b_avg<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Average number of packets bulk rate in the backward direction</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>34</td>
    <td class="xl67" x:str>flow_iat_min<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Minimum time between two packets sent in the flow</td>
    <td class="xl70" x:num>75</td>
    <td class="xl67" x:str>fwd_blk_rate_avg<span style='mso-spacerun:yes;'>&nbsp;</span></td>
    <td class="xl67" x:str>Average number of bulk rate in the forward direction</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>35</td>
    <td class="xl67" x:str>flow_iat_mean<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Mean time between two packets sent in the flow</td>
    <td class="xl70" x:num>76</td>
    <td class="xl67" x:str>bwd_blk_rate_avg<span style='mso-spacerun:yes;'>&nbsp;</span></td>
    <td class="xl67" x:str>Average number of bulk rate in the backward direction</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>36</td>
    <td class="xl67" x:str>flow_iat_std<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Standard deviation time between two packets sent in the flow</td>
    <td class="xl70" x:num>77</td>
    <td class="xl67" x:str>fwd_seg_size_avg<span style='mso-spacerun:yes;'>&nbsp;</span></td>
    <td class="xl67" x:str>Average size observed in the forward direction</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>37</td>
    <td class="xl67" x:str>fwd_iat_tot<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Total time between two packets sent in the forward direction</td>
    <td class="xl70" x:num>78</td>
    <td class="xl67" x:str>bwd_seg_size_avg<span style='mso-spacerun:yes;'>&nbsp;</span></td>
    <td class="xl67" x:str>Average size observed in the backward direction</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>38</td>
    <td class="xl67" x:str>fwd_iat_max<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Maximum time between two packets sent in the forward direction</td>
    <td class="xl70" x:num>79</td>
    <td class="xl67" x:str>subflow_fwd_pkts<span style='mso-spacerun:yes;'>&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>The average number of packets in a sub flow in the forward direction</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>39</td>
    <td class="xl67" x:str>fwd_iat_min<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Minimum time between two packets sent in the forward direction</td>
    <td class="xl70" x:num>80</td>
    <td class="xl67" x:str>subflow_bwd_pkts<span style='mso-spacerun:yes;'>&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>The average number of packets in a sub flow in the backward direction</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>40</td>
    <td class="xl67" x:str>fwd_iat_mean<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Mean time between two packets sent in the forward direction</td>
    <td class="xl70" x:num>81</td>
    <td class="xl67" x:str>subflow_fwd_byts<span style='mso-spacerun:yes;'>&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>The average number of bytes in a sub flow in the forward direction</td>
   </tr>
   <tr height="18" style='height:13.50pt;'>
    <td class="xl69" height="18" style='height:13.50pt;' x:num>41</td>
    <td class="xl67" x:str>fwd_iat_std<span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>Standard deviation time between two packets sent in the forward direction</td>
    <td class="xl70" x:num>82</td>
    <td class="xl67" x:str>subflow_bwd_byts<span style='mso-spacerun:yes;'>&nbsp;&nbsp;</span></td>
    <td class="xl67" x:str>The average number of bytes in a sub flow in the backward direction</td>
   </tr>
   <![if supportMisalignedColumns]>
    <tr width="0" style='display:none;'>
     <td width="72" style='width:54;'></td>
     <td width="137" style='width:103;'></td>
     <td width="482" style='width:362;'></td>
     <td width="72" style='width:54;'></td>
     <td width="137" style='width:103;'></td>
     <td width="802" style='width:602;'></td>
     <td width="72" style='width:54;'></td>
    </tr>
   <![endif]>
  </table>
