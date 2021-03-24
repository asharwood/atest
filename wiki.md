==  REFS Integration Test Report ==

'''Document Reference: SPICE-RAL-TR-5001'''

'''Test Personnel: Tim Grundy, Steve Guest & Sunil Sidher'''

'''Issue: 3.0'''

'''Date: 15th Aug 2014'''

'''Start Time: 10:30:00 UT'''

=== REFS Configuration ===

* Ensure that the REFS Configuration Status is consistent with the list below:

|| '''Component''' || '''surya-s2k''' || '''surya-egse''' || '''surya-qla''' || '''RALSIS PC (Ops)''' || '''TM Simulator PC''' || '''Test Passed? Yes / No''' ||
|| Operating System || OpenSUSE 11.1 (32-bit) || OpenSUSE 12.3 || OpenSUSE 12.3 || Windows 7 || Not used || Yes ||
|| Java            || Java(TM) SE Runtime Environment (build 1.7.0_67-b01) || Java(TM) SE Runtime Environment (build 1.7.0_67-b01) || Java(TM) SE Runtime Environment (1.7.0_67-b01) || - || - ||
Yes ||
|| SCOS-EGSE       || V1.5 (rebuilt by Nicholas Mecredy for SoLO)      ||     -            ||    -            || - || - || Yes ||
|| SPICE Database (MIB) || V4.40 ||     -     ||    -     || - || - || Yes ||
|| EGSE Gateway    || hcss-13.0.3244 ||     -     ||    -     || - || - || Yes ||
|| EGSE Router     ||        -         || hcss-13.0.3244 ||     -       || - || - || Yes ||
|| Packet Display    ||        -         || hcss-13.0.3244 ||    -       || - || - || Yes ||
|| QLA     ||        -         || V0.4 August 2014 [http://surya-egse.ag.rl.ac.uk:8080/jenkins/job/spice_qla/ spice_qla build #65] || V0.4 August 2014  [http://surya-egse.ag.rl.ac.uk:8080/jenkin
s/job/spice_qla/ spice_qla build #65]      || - || - || Yes ||
|| SPICE Data Model (XTCE)    ||        -         || [http://surya-egse.ag.rl.ac.uk:8080/jenkins/job/spice_model/ spice_model build #44 ] || [http://surya-egse.ag.rl.ac.uk:8080/jenkins/job/spice
_model/ spice_model build #44]      || - || - || Yes ||
|| TM Ingestion  ||      -     || [http://surya-egse.ag.rl.ac.uk:8080/jenkins/job/spice_ingest/ spice_ingest build #44]  ||   -  || - || - || Yes ||
|| RALSIS Database (MIB)     || V1.1     ||                 -     ||   -     || - || - || Yes ||
|| RALSIS      ||      -     ||                 -     ||   -     || V 0.7.0 || - || Yes ||
|| TM Simulator     ||      -     ||                 -     ||   -     || - || - || Yes ||

 * '''SCOS Session Name:''' 2014_08_14_10_28_ccscond_surya-s2k_REALTIME

=== SPICE Instrument Configuration ===
