# SyncFusion-SfSwitch-issue
Test project for reproducing accessibility issue with SyncFusion SfSwitch control.

Android TalkBack will read "Switch Off state selected", however when switch is enabled for first time, TalkBack reads nothing back. Turning off again will read "Switch Off state selected", and turning back on will then read "Switch On state selected".
This issue only shows on the first time the SfSwitch is switched to the ON state.
