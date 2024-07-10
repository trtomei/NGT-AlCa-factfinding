# About RawPrime/Buffer

- What is the ultimate goal of Raw Prime (is it to reduce the event size to
    fit within daq limit or offline tape/disk limits or to reduce the buffer
    needs of Thiago's project or all three)?
- Is there a plan to make HLT run with this Raw prime format (instead of Raw)?
      o If No, how can we re-run HLT if we are only saving in Raw prime? (eg:
        how do we do Full Track Validations with Muon dataset for example
        <https://its.cern.ch/jira/browse/CMSALCA-283?focusedId=6430848&page=com.atlassian.jira.plugin.system.issuetabpanels%3Acomment-tabpanel#comment-6430848> .
        I assume HLT_Physics will still be with Raw)?
      o If yes, then can this running of HLT after buffer be also be done in
        RawPrime. ie Leve1 1 => Level 2 (Raw Prime , buffer 8 hrs) => HLT . This
        way , both prompt reco and HLT will be Raw Prime input which may be better?


# About the demonstrator (Thiago/Marco)  that is planned for next year:

- The aim is to run only scouting for this 300 Hz?
      o Wont it be better to have also this reconstructed offline (maybe not 300
        Hz but ~30 Hz similar to what ScoutingPFMonitor does) ?
      o My point is if the goal is to have offline like calibrations , then wont
        the comparison b/w the turn ons of /Normal Scouting/ w.r.to /offline
        object (ie the current turn ons) vs NGT Scouting (with offline like
        calibrations) w.r.to offline/ be a better demonstrator?
