---
title: ""
date: 2020-11-23T18:30:49-05:00

menu:
  main:
    name: "Home"
    weight: 1

---

{{< image frame="false" width="11em" src="img/ShertzerAllison.jpg" float="right" alt="Picture of me" >}}

Associate Professor, Department of Economics, University of Pittsburgh

Office: Posvar 4509  
Phone: 412-648-7071  
Email: shertzer@pitt.edu  
[Curriculum Vitae](https://www.allisonshertzer.com/files/ShertzerAllison_CV.pdf)


I put your CV stuff here in two different ways, you can do either one you want.

The natural Markdown way, you'll get something like you had before:

# Employment and Affiliations
 - Associate Professor of Economics, University of Pittsburgh, September 2019 - present
 - Research Associate, National Bureau of Economic Research, October 2019 - present

# Education
 - Ph.D. Economics, UCLA, June 2011
 - M.A. Economics, UCLA, December 2007
 - B.S. Industrial Engineering, B.A. Mathematics, Arizona State University, summa cum laude, May 2006

You can knock those headers down a couple notches if you want, like this:

## Employment and Affiliations (one tick smaller)
 - Associate Professor of Economics, University of Pittsburgh, September 2019 - present
 - Research Associate, National Bureau of Economic Research, October 2019 - present

### Education (two ticks smaller)
 - Ph.D. Economics, UCLA, June 2011
 - M.A. Economics, UCLA, December 2007
 - B.S. Industrial Engineering, B.A. Mathematics, Arizona State University, summa cum laude, May 2006

This theme also has a kind of nifty "resume" feature. The same thing using that is below:

{{< container >}}
  {{< resume-section title="Employment and Affiliations" >}}
    {{< resume-entry what="Associate Professor of Economics"
                     where="University of Pittsburgh"
                     when="September 2019-present">}}
    {{< /resume-entry >}}
    {{< resume-entry what="Research Associate"
                     where="National Bureau of Economic Research"
                     when="October 2019-present">}}
    {{< /resume-entry >}}
  {{< /resume-section >}}
  {{< resume-section title="Education" >}}
    {{< resume-entry what="Ph.D. Economics"
                     where="UCLA"
                     when="June 2011">}}
    {{< /resume-entry >}}
    {{< resume-entry what="M.A. Economics"
                     where="UCLA"
                     when="December 2007">}}
    {{< /resume-entry >}}
    {{< resume-entry what="B.S. Industrial Engineering, B.A. Mathematics"
                     where="Arizona State University"
                     when="May 2006">}}
    {{< /resume-entry >}}
  {{< /resume-section >}}
{{< /container >}}

You might consider some kind of text or introduction on your home page to fill
in the space by your picture up on the top. Along the lines of "I research 
economics, and I write, stuff, and I cook all cuisines, and I lose at MarioKart
to my brother." Something like that.
