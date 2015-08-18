# Rosettacode: 100 doors in Ceylon

[http://rosettacode.org/wiki/100_doors#Ceylon](http://rosettacode.org/wiki/100_doors#Ceylon)

## Task description

**Problem:** You have 100 doors in a row that are all initially closed. You make 100 passes by the doors. The first time through, you visit every door and toggle the door (if the door is closed, you open it; if it is open, you close it). The second time you only visit every 2nd door (door #2, #4, #6, ...). The third time, every 3rd door (door #3, #6, #9, ...), etc, until you only visit the 100th door.

**Question:** What state are the doors in after the last pass? Which are open, which are closed?

**[Alternate][1]** As noted in this page's [discussion page][2], the only doors that remain open are whose numbers are perfect squares of integers. Opening only those doors is an [optimization][3] that may also be expressed.

[1]: http://rosettacode.org/wiki/Rosetta_Code:Extra_credit
[2]: http://rosettacode.org/wiki/Talk:100_doors
[3]: http://rosettacode.org/wiki/Rosetta_Code:Optimization

## Implementation

**Code:** [run.ceylon](run.ceylon)

**Output:**

    Open doors (naive):     { 1, 4, 9, 16, 25, 36, 49, 64, 81, 100 }
    Open doors (optimized): { 1, 4, 9, 16, 25, 36, 49, 64, 81, 100 }
