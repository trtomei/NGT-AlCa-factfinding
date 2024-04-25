# Random points from a private conversation

Proposal: we can collect 1% of the 30 kHz that go into scouting, and re-run the HLT Scouting over them "later" ?
 - then we could just send 300 Hz of Scouting to Parking, and use that
 - but the point of next year's milestone is to show that we can build a system that does this "properly" (even if just on a single slice)
 - it's pretty obvious that we can re-run the HLT later over RAW data with updated conditions... if that's the only thing that we show, I wouldn't call it much of a success

We should really focus on the "delayed real time" nature of the beast:
 - one task is to buffer data for 8 hours (or any other delay)
 - one task is to derive updated calibrations within 8 hours
 - one task is to run a second HLT step over the buffered data
