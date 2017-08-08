Variablen-Übersicht
===================

<div
style="width: 200px; float: right; overflow: hidden; margin-left: 20px; border-left: 2px solid #CCCCCC; padding: 0px 0px 10px 10px">

Falls die Liste ausgedruckt werden soll, öffnet SoSci Survey die Liste
gerne für Sie in einem neuen Fenster und ohne Rahmen.

<div style="margin-bottom: 20px">

</div>

Für eine druckfähige Übersicht der Fragen, verwenden Sie die
Korrekturfahne des entsprechenden Fragebogens.

[![All](../layout/button.print.png "Druckansicht (gesamter Fragebogen)")
qnr2](preview.php?questionnaire=qnr2 "Fragebogen")
[![All](../layout/button.print.png "Druckansicht (gesamter Fragebogen)")
sociodemographics](preview.php?questionnaire=sociodemographics "Soziodemografie (Demonstration)")

</div>

In der Variablen-Übersicht sind alle Variablen aufgeführt, die im Rahmen
des Befragungsprojekts verwendet werden. Der Fragenkatalog und damit
auch die Variablen sind nach Rubrik, Position der Frage und des Items
sortiert.

In der Übersicht sind neben den Variablen auch die möglichen
Ausprägungen angegeben. Weitere Informationen zu den Werten stehen in
der Anleitung.

[Kodierung und
Rückgabewerte](https://www.soscisurvey.de/help/doku.php/de:results:values){.help}

Variablen, für die bisher keine Werte gespeichert wurden, sind
ausgegraut. Diese Variablen werden erst aktiv verwendet, sobald in
mindestens einem ausgefüllten Fragebogen ein Wert dafür angegeben wird.

Die Übersicht wird in der aktiven Sprachversion angezeigt.

<div style="clear: both">

</div>

Fragebogen-Interne Daten
------------------------

<div class="variables">

<div class="question">

Im Datensatz finden Sie neben Ihren Fragen folgende zusätzliche
Variablen, sofern Sie die entsprechende Option beim Herunterladen des
Datensatzes nicht deaktivieren.

<div class="items">

**CASE** Fortlaufende Nummer der Versuchsperson

**REF** Referenz, falls solch eine im Link zum Fragebogen übergeben
wurde

**LASTPAGE** Nummer der Seite im Fragebogens, die zuletzt bearbeitet und
abgeschickt wurde

**QUESTNNR** Kennung des Fragebogens, der bearbeitet wurde

**MODE** Information, ob der Fragebogen im Pretest oder durch einen
Projektmitarbeiter gestartet wurde

**STARTED** Zeitpunkt, zu dem der Teilnehmer den Fragebogen aufgerufen
hat

**FINISHED** Information, ob der Fragebogen bis zur letzten Seite
ausgefüllt wurde

**TIME\_001...** Zeit, die ein Teilnehmer auf einer Fragebogen-Seite
verbracht hat

Bitte beachten Sie, dass Sie die Fragebogen-internen Variablen nicht mit
der Funktion value() auslesen können. Für Interview-Nummer und Referenz
stehen aber die PHP-Funktionen [PHP-Funktion
caseNumber()](https://www.soscisurvey.de/help/doku.php/de:create:functions:casenumber){.help}
und [PHP-Funktion
reference()](https://www.soscisurvey.de/help/doku.php/de:create:functions:reference){.help}
zur Verfügung.

Details über die zusätzlichen Variablen stehen in der Anleitung:
[Zusätzliche Variablen in der
Datenausgabe](https://www.soscisurvey.de/help/doku.php/de:results:variables){.help}

</div>

</div>

</div>

Section NO: Nootropics Taken {#section-no-nootropics-taken style="margin-top: 32px"}
----------------------------

<div class="variables">

<div class="question">

[\[NO01\]]{.ident} Multiple Choice

Nootropics taken

"Which of these following nootropics have you already taken?"

**NO01** Nootropics taken: Residual option (negative) or number of
selected options

Integer

<div class="items">

**NO01\_01** L-Theanine

**NO01\_02** Bacopa Monnieri

**NO01\_03** Caffeine

**NO01\_04** Curcumin

**NO01\_05** Ashwagandha

**NO01\_06** Rhodiola rosea

**NO01\_07** St John's Wort

**NO01\_08** Kava

**NO01\_09** Methylphenidate

**NO01\_10** Adderall

**NO01\_11** L-Deprenyl

**NO01\_12** Tyrosine

**NO01\_13** N-Acetyl-L-Tyrosine

**NO01\_14** Creatine

**NO01\_15** CDP-Choline

**NO01\_16** Alpha-GPC

**NO01\_17** Carnitine / Acetyl-L-Carnitine

**NO01\_18** Omega-3 Supplements

**NO01\_19** Magnesium

**NO01\_20** Modafinil

**NO01\_21** Armodafinil

**NO01\_22** Adrafinil

**NO01\_24** Piracetam

**NO01\_25** Phenylpiracetam

**NO01\_26** Aniracetam

**NO01\_27** Oxiracetam

**NO01\_28** Pramiracetam

**NO01\_29** Coluracetam

**NO01\_30** Fasoracetam

**NO01\_31** Nefiracetam

**NO01\_32** Noopept

**NO01\_33** Semax

**NO01\_34** Selank

**NO01\_35** Doepezil

**NO01\_36** Huperzine A

**NO01\_37** Ampalex

**NO01\_38** Tianetpine

**NO01\_39** NSI-189

**NO01\_40** Melatonin

**NO01\_41** GABA

**NO01\_42** 5-HTP

**NO01\_43** Black Seed Oil

**NO01\_44** Ginseng

**NO01\_45** Ginkgo biloba

**NO01\_46** Nicotine

**NO01\_47** Sulbutiamine

**NO01\_48** Uridine

**NO01\_49** Sarcosine

**NO01\_50** Sunifiram

**NO01\_51** BPC-157

**NO01\_52** Boswellia

**NO01\_54** Guanfacine

**NO01\_55** DMHA

**NO01\_56** LSD Microdose

**NO01\_57** CBD Oil

**NO01\_58** PRL-8-53

**NO01\_59** Agmatine

**NO01\_60** Selegiline

**NO01\_61** Phenibut

**NO01\_62** Lion's Mane

**NO01\_63** Methylene blue

1 = Not checked\
2 = Checked

</div>

</div>

</div>

Section NR: Nootropics Rating {#section-nr-nootropics-rating style="margin-top: 32px"}
-----------------------------

<div class="variables">

<div class="question">

[\[NR01\]]{.ident} Scale (fully labeled)

Nootropics Satisfaction

"People can have pleasant or unpleasant experiences with their
nootropics."

<div class="items">

**NR01\_01** L-Theanine

**NR01\_02** Bacopa Monnieri

**NR01\_03** Caffeine

**NR01\_04** Curcumin

**NR01\_05** Ashwagandha

**NR01\_06** Rhodiola rosea

**NR01\_07** St John's Wort

**NR01\_08** Kava

**NR01\_09** Methylphenidate

**NR01\_10** Adderall

**NR01\_11** L-Deprenyl

**NR01\_12** Tyrosine

**NR01\_13** N-Acetyl-L-Tyrosine

**NR01\_14** Creatine

**NR01\_15** CDP-Choline

**NR01\_16** Alpha-GPC

**NR01\_17** Carnitine / Acetyl-L-Carnitine

**NR01\_18** Omega-3 Supplements

**NR01\_19** Magnesium

**NR01\_20** Modafinil

**NR01\_21** Armodafinil

**NR01\_22** Adrafinil

**NR01\_24** Piracetam

**NR01\_25** Phenylpiracetam

**NR01\_26** Aniracetam

**NR01\_27** Oxiracetam

**NR01\_28** Pramiracetam

**NR01\_29** Coluracetam

**NR01\_30** Fasoracetam

**NR01\_31** Nefiracetam

**NR01\_32** Noopept

**NR01\_33** Semax

**NR01\_34** Selank

**NR01\_35** Doepezil

**NR01\_36** Huperzine A

**NR01\_37** Ampalex

**NR01\_38** Tianetpine

**NR01\_39** NSI-189

**NR01\_40** Melatonin

**NR01\_41** GABA

**NR01\_42** 5-HTP

**NR01\_43** Black Seed Oil

**NR01\_44** Ginseng

**NR01\_45** Ginkgo biloba

**NR01\_46** Nicotine

**NR01\_47** Sulbutiamine

**NR01\_48** Uridine

**NR01\_49** Sarcosine

**NR01\_50** Sunifiram

**NR01\_51** BPC-157

**NR01\_52** Boswellia

**NR01\_54** Guanfacine

**NR01\_55** DMHA

**NR01\_56** LSD Microdose

**NR01\_57** CBD Oil

**NR01\_58** PRL-8-53

**NR01\_59** Agmatine

**NR01\_60** Selegiline / Deprenyl

**NR01\_61** Phenibut

**NR01\_62** Lion's Mane

**NR01\_63** Methylene blue

1 = Very unpleasant\
2 = Moderately unpleasant\
3 = Slightly unpleasant\
4 = Neutral\
5 = Slightly pleasant\
6 = Moderately pleasant\
7 = Very pleasant\
-9 = Not answered

</div>

</div>

<div class="question">

[\[NR02\]]{.ident} Scale (fully labeled)

Nootropics Focus

"Some nootropics are used to improve focus. They are meant to help with
concentration and to reduce "brain fog"."

<div class="items">

**NR02\_01** L-Theanine

**NR02\_02** Bacopa Monnieri

**NR02\_03** Caffeine

**NR02\_04** Curcumin

**NR02\_05** Ashwagandha

**NR02\_06** Rhodiola rosea

**NR02\_07** St John's Wort

**NR02\_08** Kava

**NR02\_09** Methylphenidate

**NR02\_10** Adderall

**NR02\_11** L-Deprenyl

**NR02\_12** Tyrosine

**NR02\_13** N-Acetyl-L-Tyrosine

**NR02\_14** Creatine

**NR02\_15** CDP-Choline

**NR02\_16** Alpha-GPC

**NR02\_17** Carnitine / Acetyl-L-Carnitine

**NR02\_18** Omega-3 Supplements

**NR02\_19** Magnesium

**NR02\_20** Modafinil

**NR02\_21** Armodafinil

**NR02\_22** Adrafinil

**NR02\_24** Piracetam

**NR02\_25** Phenylpiracetam

**NR02\_26** Aniracetam

**NR02\_27** Oxiracetam

**NR02\_28** Pramiracetam

**NR02\_29** Coluracetam

**NR02\_30** Fasoracetam

**NR02\_31** Nefiracetam

**NR02\_32** Noopept

**NR02\_33** Semax

**NR02\_34** Selank

**NR02\_35** Doepezil

**NR02\_36** Huperzine A

**NR02\_37** Ampalex

**NR02\_38** Tianetpine

**NR02\_39** NSI-189

**NR02\_40** Melatonin

**NR02\_41** GABA

**NR02\_42** 5-HTP

**NR02\_43** Black Seed Oil

**NR02\_44** Ginseng

**NR02\_45** Ginkgo biloba

**NR02\_46** Nicotine

**NR02\_47** Sulbutiamine

**NR02\_48** Uridine

**NR02\_49** Sarcosine

**NR02\_50** Sunifiram

**NR02\_51** BPC-157

**NR02\_52** Boswellia

**NR02\_54** Guanfacine

**NR02\_55** DMHA

**NR02\_56** LSD Microdose

**NR02\_57** CBD Oil

**NR02\_58** PRL-8-53

**NR02\_59** Agmatine

**NR02\_60** Selegiline / Deprenyl

**NR02\_61** Phenibut

**NR02\_62** Lion's Mane

**NR02\_63** Methylene blue

1 = Strong decrease\
2 = Moderate decrease\
3 = Slight decrease\
4 = No effect\
5 = Slight increase\
6 = Moderate increase\
7 = Strong increase\
-9 = Not answered

</div>

</div>

<div class="question">

[\[NR03\]]{.ident} Scale (fully labeled)

Nootropics Memory

"Some nootropics are used to improve memory. They are meant to help
people remember things more easily and to..."

<div class="items">

**NR03\_01** L-Theanine

**NR03\_02** Bacopa Monnieri

**NR03\_03** Caffeine

**NR03\_04** Curcumin

**NR03\_05** Ashwagandha

**NR03\_06** Rhodiola rosea

**NR03\_07** St John's Wort

**NR03\_08** Kava

**NR03\_09** Methylphenidate

**NR03\_10** Adderall

**NR03\_11** L-Deprenyl

**NR03\_12** Tyrosine

**NR03\_13** N-Acetyl-L-Tyrosine

**NR03\_14** Creatine

**NR03\_15** CDP-Choline

**NR03\_16** Alpha-GPC

**NR03\_17** Carnitine / Acetyl-L-Carnitine

**NR03\_18** Omega-3 Supplements

**NR03\_19** Magnesium

**NR03\_20** Modafinil

**NR03\_21** Armodafinil

**NR03\_22** Adrafinil

**NR03\_24** Piracetam

**NR03\_25** Phenylpiracetam

**NR03\_26** Aniracetam

**NR03\_27** Oxiracetam

**NR03\_28** Pramiracetam

**NR03\_29** Coluracetam

**NR03\_30** Fasoracetam

**NR03\_31** Nefiracetam

**NR03\_32** Noopept

**NR03\_33** Semax

**NR03\_34** Selank

**NR03\_35** Doepezil

**NR03\_36** Huperzine A

**NR03\_37** Ampalex

**NR03\_38** Tianetpine

**NR03\_39** NSI-189

**NR03\_40** Melatonin

**NR03\_41** GABA

**NR03\_42** 5-HTP

**NR03\_43** Black Seed Oil

**NR03\_44** Ginseng

**NR03\_45** Ginkgo biloba

**NR03\_46** Nicotine

**NR03\_47** Sulbutiamine

**NR03\_48** Uridine

**NR03\_49** Sarcosine

**NR03\_50** Sunifiram

**NR03\_51** BPC-157

**NR03\_52** Boswellia

**NR03\_54** Guanfacine

**NR03\_55** DMHA

**NR03\_56** LSD Microdose

**NR03\_57** CBD Oil

**NR03\_58** PRL-8-53

**NR03\_59** Agmatine

**NR03\_60** Selegiline / Deprenyl

**NR03\_61** Phenibut

**NR03\_62** Lion's Mane

**NR03\_63** Methylene blue

1 = Strong decrease\
2 = Moderate decrease\
3 = Slight decrease\
4 = No effect\
5 = Slight increase\
6 = Moderate increase\
7 = Strong increase\
-9 = Not answered

</div>

</div>

<div class="question">

[\[NR04\]]{.ident} Scale (fully labeled)

Nootropics Mood

"Some nootropics are used to improve mood. They are taken to reduce
negative feelings and to promote happiness."

<div class="items">

**NR04\_01** L-Theanine

**NR04\_02** Bacopa Monnieri

**NR04\_03** Caffeine

**NR04\_04** Curcumin

**NR04\_05** Ashwagandha

**NR04\_06** Rhodiola rosea

**NR04\_07** St John's Wort

**NR04\_08** Kava

**NR04\_09** Methylphenidate

**NR04\_10** Adderall

**NR04\_11** L-Deprenyl

**NR04\_12** Tyrosine

**NR04\_13** N-Acetyl-L-Tyrosine

**NR04\_14** Creatine

**NR04\_15** CDP-Choline

**NR04\_16** Alpha-GPC

**NR04\_17** Carnitine / Acetyl-L-Carnitine

**NR04\_18** Omega-3 Supplements

**NR04\_19** Magnesium

**NR04\_20** Modafinil

**NR04\_21** Armodafinil

**NR04\_22** Adrafinil

**NR04\_24** Piracetam

**NR04\_25** Phenylpiracetam

**NR04\_26** Aniracetam

**NR04\_27** Oxiracetam

**NR04\_28** Pramiracetam

**NR04\_29** Coluracetam

**NR04\_30** Fasoracetam

**NR04\_31** Nefiracetam

**NR04\_32** Noopept

**NR04\_33** Semax

**NR04\_34** Selank

**NR04\_35** Doepezil

**NR04\_36** Huperzine A

**NR04\_37** Ampalex

**NR04\_38** Tianetpine

**NR04\_39** NSI-189

**NR04\_40** Melatonin

**NR04\_41** GABA

**NR04\_42** 5-HTP

**NR04\_43** Black Seed Oil

**NR04\_44** Ginseng

**NR04\_45** Ginkgo biloba

**NR04\_46** Nicotine

**NR04\_47** Sulbutiamine

**NR04\_48** Uridine

**NR04\_49** Sarcosine

**NR04\_50** Sunifiram

**NR04\_51** BPC-157

**NR04\_52** Boswellia

**NR04\_54** Guanfacine

**NR04\_55** DMHA

**NR04\_56** LSD Microdose

**NR04\_57** CBD Oil

**NR04\_58** PRL-8-53

**NR04\_59** Agmatine

**NR04\_60** Selegiline / Deprenyl

**NR04\_61** Phenibut

**NR04\_62** Lion's Mane

**NR04\_63** Methylene blue

1 = Strong decrease\
2 = Moderate decrease\
3 = Small decrease\
4 = No effect\
5 = Small increase\
6 = Moderate increase\
7 = Strong increase\
-9 = Not answered

</div>

</div>

<div class="question">

[\[NR05\]]{.ident} Scale (fully labeled)

Nootropics Motivation

"Some nootropics are used to improve motivation and to reduce lethargy.
They are meant to increase the drive ..."

<div class="items">

**NR05\_01** L-Theanine

**NR05\_02** Bacopa Monnieri

**NR05\_03** Caffeine

**NR05\_04** Curcumin

**NR05\_05** Ashwagandha

**NR05\_06** Rhodiola rosea

**NR05\_07** St John's Wort

**NR05\_08** Kava

**NR05\_09** Methylphenidate

**NR05\_10** Adderall

**NR05\_11** L-Deprenyl

**NR05\_12** Tyrosine

**NR05\_13** N-Acetyl-L-Tyrosine

**NR05\_14** Creatine

**NR05\_15** CDP-Choline

**NR05\_16** Alpha-GPC

**NR05\_17** Carnitine / Acetyl-L-Carnitine

**NR05\_18** Omega-3 Supplements

**NR05\_19** Magnesium

**NR05\_20** Modafinil

**NR05\_21** Armodafinil

**NR05\_22** Adrafinil

**NR05\_24** Piracetam

**NR05\_25** Phenylpiracetam

**NR05\_26** Aniracetam

**NR05\_27** Oxiracetam

**NR05\_28** Pramiracetam

**NR05\_29** Coluracetam

**NR05\_30** Fasoracetam

**NR05\_31** Nefiracetam

**NR05\_32** Noopept

**NR05\_33** Semax

**NR05\_34** Selank

**NR05\_35** Doepezil

**NR05\_36** Huperzine A

**NR05\_37** Ampalex

**NR05\_38** Tianetpine

**NR05\_39** NSI-189

**NR05\_40** Melatonin

**NR05\_41** GABA

**NR05\_42** 5-HTP

**NR05\_43** Black Seed Oil

**NR05\_44** Ginseng

**NR05\_45** Ginkgo biloba

**NR05\_46** Nicotine

**NR05\_47** Sulbutiamine

**NR05\_48** Uridine

**NR05\_49** Sarcosine

**NR05\_50** Sunifiram

**NR05\_51** BPC-157

**NR05\_52** Boswellia

**NR05\_54** Guanfacine

**NR05\_55** DMHA

**NR05\_56** LSD Microdose

**NR05\_57** CBD Oil

**NR05\_58** PRL-8-53

**NR05\_59** Agmatine

**NR05\_60** Selegiline / Deprenyl

**NR05\_61** Phenibut

**NR05\_62** Lion's Mane

**NR05\_63** Methylene blue

1 = Strong decrease\
2 = Moderate decrease\
3 = Small decrease\
4 = No effect\
5 = Small increase\
6 = Moderate increase\
7 = Strong increase\
-9 = Not answered

</div>

</div>

<div class="question">

[\[NR06\]]{.ident} Scale (fully labeled)

Nootropics Anxiety

"Some nootropics are taken to reduce anxiety and stress. They are
thought to make people feel relaxed and calm."

<div class="items">

**NR06\_01** L-Theanine

**NR06\_02** Bacopa Monnieri

**NR06\_03** Caffeine

**NR06\_04** Curcumin

**NR06\_05** Ashwagandha

**NR06\_06** Rhodiola rosea

**NR06\_07** St John's Wort

**NR06\_08** Kava

**NR06\_09** Methylphenidate

**NR06\_10** Adderall

**NR06\_11** L-Deprenyl

**NR06\_12** Tyrosine

**NR06\_13** N-Acetyl-L-Tyrosine

**NR06\_14** Creatine

**NR06\_15** CDP-Choline

**NR06\_16** Alpha-GPC

**NR06\_17** Carnitine / Acetyl-L-Carnitine

**NR06\_18** Omega-3 Supplements

**NR06\_19** Magnesium

**NR06\_20** Modafinil

**NR06\_21** Armodafinil

**NR06\_22** Adrafinil

**NR06\_24** Piracetam

**NR06\_25** Phenylpiracetam

**NR06\_26** Aniracetam

**NR06\_27** Oxiracetam

**NR06\_28** Pramiracetam

**NR06\_29** Coluracetam

**NR06\_30** Fasoracetam

**NR06\_31** Nefiracetam

**NR06\_32** Noopept

**NR06\_33** Semax

**NR06\_34** Selank

**NR06\_35** Doepezil

**NR06\_36** Huperzine A

**NR06\_37** Ampalex

**NR06\_38** Tianetpine

**NR06\_39** NSI-189

**NR06\_40** Melatonin

**NR06\_41** GABA

**NR06\_42** 5-HTP

**NR06\_43** Black Seed Oil

**NR06\_44** Ginseng

**NR06\_45** Ginkgo biloba

**NR06\_46** Nicotine

**NR06\_47** Sulbutiamine

**NR06\_48** Uridine

**NR06\_49** Sarcosine

**NR06\_50** Sunifiram

**NR06\_51** BPC-157

**NR06\_52** Boswellia

**NR06\_54** Guanfacine

**NR06\_55** DMHA

**NR06\_56** LSD Microdose

**NR06\_57** CBD Oil

**NR06\_58** PRL-8-53

**NR06\_59** Agmatine

**NR06\_60** Selegiline / Deprenyl

**NR06\_61** Phenibut

**NR06\_62** Lion's Mane

**NR06\_63** Methylene blue

1 = Strong increase\
2 = Moderate increase\
3 = Small increase\
4 = No effect\
5 = Small decrease\
6 = Moderate decrease\
7 = Strong decrease\
-9 = Not answered

</div>

</div>

</div>

Section BF: Short Big Five {#section-bf-short-big-five style="margin-top: 32px"}
--------------------------

<div class="variables">

<div class="question">

[\[BF01\]]{.ident} Scale (fully labeled)

BFI

"Here are a number of traits that may or may not apply to you. Please
rate each statement to indicate the ext..."

<div class="items">

**BF01\_01** am the life of the party.

**BF01\_02** sympathize with oter's feelings.

**BF01\_03** get chores done right away.

**BF01\_04** have frequent mood swings.

**BF01\_05** have a vivid imagination.

**BF01\_06** don't talk a lot.

**BF01\_07** am not interested in other people's problems.

**BF01\_08** often forget to put things back in their proper place.

**BF01\_09** am relaxed most of the time.

**BF01\_10** am not interested in abstract ideas.

**BF01\_11** talk to a lot of different people at parties.

**BF01\_12** feel other's emotions.

**BF01\_13** like order.

**BF01\_14** get upset easily.

**BF01\_15** have difficulty understanding abstract ideas.

**BF01\_16** keep in the background.

**BF01\_17** am not really interested in others.

**BF01\_18** make a mess of things.

**BF01\_19** seldom feel blue.

**BF01\_20** do not have a good imagination.

1 = very inaccurate\
2 = moderately inaccurate\
3 = neither inaccurate nor accurate\
4 = moderately accurate\
5 = very accurate\
-9 = Not answered

</div>

</div>

</div>

Section ND: Nootropics Dose {#section-nd-nootropics-dose style="margin-top: 32px"}
---------------------------

<div class="variables">

<div class="question">

[\[ND01\]]{.ident} Text Input

Nootropics dose

"What was the dose (in mg) of the nootropics you've taken?"

<div class="items">

**ND01\_01** L-Theanine

**ND01\_02** Bacopa Monnieri

**ND01\_03** Caffeine

**ND01\_04** Curcumin

**ND01\_05** Ashwagandha

**ND01\_06** Rhodiola rosea

**ND01\_07** St John's Wort

**ND01\_08** Kava

**ND01\_09** Methylphenidate

**ND01\_10** Adderall

**ND01\_11** L-Deprenyl

**ND01\_12** Tyrosine

**ND01\_13** N-Acetyl-L-Tyrosine

**ND01\_14** Creatine

**ND01\_15** CDP-Choline

**ND01\_16** Alpha-GPC

**ND01\_17** Carnitine / Acetyl-L-Carnitine

**ND01\_18** Omega-3 Supplements

**ND01\_19** Magnesium

**ND01\_20** Modafinil

**ND01\_21** Armodafinil

**ND01\_22** Adrafinil

**ND01\_24** Piracetam

**ND01\_25** Phenylpiracetam

**ND01\_26** Aniracetam

**ND01\_27** Oxiracetam

**ND01\_28** Pramiracetam

**ND01\_29** Coluracetam

**ND01\_30** Fasoracetam

**ND01\_31** Nefiracetam

**ND01\_32** Noopept

**ND01\_33** Semax

**ND01\_34** Selank

**ND01\_35** Doepezil

**ND01\_36** Huperzine A

**ND01\_37** Ampalex

**ND01\_38** Tianetpine

**ND01\_39** NSI-189

**ND01\_40** Melatonin

**ND01\_41** GABA

**ND01\_42** 5-HTP

**ND01\_43** Black Seed Oil

**ND01\_44** Ginseng

**ND01\_45** Ginkgo biloba

**ND01\_46** Nicotine

**ND01\_47** Sulbutiamine

**ND01\_48** Uridine

**ND01\_49** Sarcosine

**ND01\_50** Sunifiram

**ND01\_51** BPC-157

**ND01\_52** Boswellia

**ND01\_54** Guanfacine

**ND01\_55** DMHA

**ND01\_56** LSD Microdose

**ND01\_57** CBD Oil

**ND01\_58** PRL-8-53

**ND01\_59** Agmatine

**ND01\_60** Selegiline / Deprenyl

**ND01\_61** Phenibut

**ND01\_62** Lion's Mane

Free text

**ND01\_01a** L-Theanine: I don't remember.

**ND01\_02a** Bacopa Monnieri: I don't remember.

**ND01\_03a** Caffeine: I don't remember.

**ND01\_04a** Curcumin: I don't remember.

**ND01\_05a** Ashwagandha: I don't remember.

**ND01\_06a** Rhodiola rosea: I don't remember.

**ND01\_07a** St John's Wort: I don't remember.

**ND01\_08a** Kava: I don't remember.

**ND01\_09a** Methylphenidate: I don't remember.

**ND01\_10a** Adderall: I don't remember.

**ND01\_11a** L-Deprenyl: I don't remember.

**ND01\_12a** Tyrosine: I don't remember.

**ND01\_13a** N-Acetyl-L-Tyrosine: I don't remember.

**ND01\_14a** Creatine: I don't remember.

**ND01\_15a** CDP-Choline: I don't remember.

**ND01\_16a** Alpha-GPC: I don't remember.

**ND01\_17a** Carnitine / Acetyl-L-Carnitine: I don't remember.

**ND01\_18a** Omega-3 Supplements: I don't remember.

**ND01\_19a** Magnesium: I don't remember.

**ND01\_20a** Modafinil: I don't remember.

**ND01\_21a** Armodafinil: I don't remember.

**ND01\_22a** Adrafinil: I don't remember.

**ND01\_24a** Piracetam: I don't remember.

**ND01\_25a** Phenylpiracetam: I don't remember.

**ND01\_26a** Aniracetam: I don't remember.

**ND01\_27a** Oxiracetam: I don't remember.

**ND01\_28a** Pramiracetam: I don't remember.

**ND01\_29a** Coluracetam: I don't remember.

**ND01\_30a** Fasoracetam: I don't remember.

**ND01\_31a** Nefiracetam: I don't remember.

**ND01\_32a** Noopept: I don't remember.

**ND01\_33a** Semax: I don't remember.

**ND01\_34a** Selank: I don't remember.

**ND01\_35a** Doepezil: I don't remember.

**ND01\_36a** Huperzine A: I don't remember.

**ND01\_37a** Ampalex: I don't remember.

**ND01\_38a** Tianetpine: I don't remember.

**ND01\_39a** NSI-189: I don't remember.

**ND01\_40a** Melatonin: I don't remember.

**ND01\_41a** GABA: I don't remember.

**ND01\_42a** 5-HTP: I don't remember.

**ND01\_43a** Black Seed Oil: I don't remember.

**ND01\_44a** Ginseng: I don't remember.

**ND01\_45a** Ginkgo biloba: I don't remember.

**ND01\_46a** Nicotine: I don't remember.

**ND01\_47a** Sulbutiamine: I don't remember.

**ND01\_48a** Uridine: I don't remember.

**ND01\_49a** Sarcosine: I don't remember.

**ND01\_50a** Sunifiram: I don't remember.

**ND01\_51a** BPC-157: I don't remember.

**ND01\_52a** Boswellia: I don't remember.

**ND01\_54a** Guanfacine: I don't remember.

**ND01\_55a** DMHA: I don't remember.

**ND01\_56a** LSD Microdose: I don't remember.

**ND01\_57a** CBD Oil: I don't remember.

**ND01\_58a** PRL-8-53: I don't remember.

**ND01\_59a** Agmatine: I don't remember.

**ND01\_60a** Selegiline / Deprenyl: I don't remember.

**ND01\_61a** Phenibut: I don't remember.

**ND01\_62a** Lion's Mane: I don't remember.

1 = Not checked\
2 = Checked

</div>

</div>

</div>

Section SD: Soziodemografie {#section-sd-soziodemografie style="margin-top: 32px"}
---------------------------

<div class="variables">

<div class="question">

[\[SD01\]]{.ident} Selection

Geschlecht

"What is your gender?"

**SD01** Geschlecht

1 = female\
2 = male\
3 = other (please specify)\
-9 = Not answered

<div class="items">

**SD01\_03** other (please specify)

Free text

</div>

</div>

<div class="question">

[\[SD02\]]{.ident} Cloze Text

Alter (direkt)

"How old are you?"

<div class="items">

**SD02\_01** I am ... years old

Free input (integer)

</div>

</div>

<div class="question">

[\[SD03\]]{.ident} Dropdown Selection

Alter (Kategorien, 5 Jahre)

"How old are you?"

**SD03** Alter (Kategorien, 5 Jahre)

1 = younger than 15 years old\
2 = 15 to 19 years old\
3 = 20 to 24 years old\
4 = 25 to 29 years old\
5 = 30 to 34 years old\
6 = 35 to 39 years old\
7 = 40 to 44 years old\
8 = 45 to 49 years old\
9 = 50 to 54 years old\
10 = 55 to 59 years old\
11 = 60 to 64 years old\
12 = 65 years or older\
-9 = Not answered

</div>

<div class="question">

[\[SD04\]]{.ident} Text Input

Alter (Geburtsjahr)

"What is your year of birth?"

<div class="items">

**SD04\_01** Year of birth

Free text

</div>

</div>

<div class="question">

[\[SD05\]]{.ident} Dropdown Selection

Geschlecht (zum kombinieren)

"Finally, we'd like to ask you for some details about yourself."

**SD05** Geschlecht (zum kombinieren)

1 = female\
2 = male\
-9 = Not answered

</div>

<div class="question">

[\[SD06\]]{.ident} Text Input

Alter (zum kombinieren)

"This question is intended to be attached to the question "Gender (to be
combined)". Please also see the exam..."

<div class="items">

**SD06\_01** How old are you? ... years old

Free input (integer)

</div>

</div>

<div class="question">

[\[SD07\]]{.ident} Selection

Land (D/A/CH)

"Which country are you currently living in?"

**SD07** Land (D/A/CH)

1 = Germany\
2 = Austria\
3 = Switzerland\
4 = Other country:\
-9 = Not answered

<div class="items">

**SD07\_04** Other country

Free text

</div>

</div>

<div class="question">

[\[SD08\]]{.ident} Suggesting Text Input

Land (weltweit, in de+en)

"Which is the country, you're currently living?"

**SD08** Land (weltweit, in de+en)

1001 = Apsny\
4 = Afghanestan\
8 = Albania\
10 = Antarctic\
12 = Algeria\
16 = American Samoa\
20 = Andorra\
24 = Angola\
660 = Anguilla\
28 = Antigua and Barbuda\
32 = Argentina\
51 = Armenia\
533 = Aruba\
36 = Australia\
40 = Austria\
31 = Azerbaijan\
44 = Bahamas\
48 = Bahrain\
50 = Bangladesch\
52 = Barbados\
112 = Belarus\
56 = Belgium\
248 = Åland Islands\
84 = Belize\
204 = Benin\
60 = Bermuda\
64 = Bhutan\
68 = Bolivia\
535 = Caribbean Netherlands\
70 = Bosnia and Herzegovina\
72 = Botswana\
76 = Brasil\
74 = Bouvet Islands\
92 = British Virgin Islands\
96 = Brunei\
86 = British Indian Ocean Territory\
100 = Bulgaria\
854 = Burkina Faso\
104 = Burma\
108 = Burundi\
116 = Cambodia\
120 = Cameroons\
124 = Canada\
132 = Cape Verde\
136 = Cayman Islands\
140 = Central African Republic\
148 = Chad\
152 = Chile\
156 = China (People's Republic of China)\
162 = Christmas Island\
166 = Cocos Islands\
170 = Colombia\
174 = Comoros\
178 = Republic of the Congo\
180 = Democratic Republic of the Congo\
184 = Cook Islands\
188 = Costa Rica\
384 = Côte d'Ivoire\
191 = Croatia\
192 = Cuba\
531 = Curaçao\
196 = Cyprus\
203 = Czech Republic\
208 = Denmark\
262 = Djibouti\
212 = Dominica\
214 = Dominican Republic\
626 = East Timor\
218 = Ecuador\
818 = Egypt\
222 = El Salvador\
226 = Equatorial Guinea\
232 = Eritrea\
233 = Estonia\
231 = Ethiopia\
238 = Falkland Islands\
234 = Faroe Islands\
583 = Federated States of Micronesia\
242 = Fiji\
246 = Finland\
250 = France\
254 = French Guiana\
258 = French Polynesia\
260 = French Southern Territories\
266 = Gabon\
270 = Gambia\
268 = Georgia\
276 = Germany\
288 = Ghana\
292 = Gibraltar\
300 = Greece\
304 = Greenland\
308 = Grenada\
312 = Guadeloupe\
316 = Guam\
320 = Guatemala\
831 = Guernsey\
324 = Guinea\
624 = Guinea-Bissau\
328 = Guyana\
\[...\]\
-1 = No answer\
-2 = other text response\
-9 = Not answered

**SD08s** Land (weltweit, in de+en) (free text)

Free text

</div>

<div class="question">

[\[SD09\]]{.ident} Cloze Text

Ort (PLZ)

"What are the first two digits of your postal code?"

<div class="items">

**SD09\_01** My zip code starts with the digits ... \*\*\*

Free text

</div>

</div>

<div class="question">

[\[SD10\]]{.ident} Selection

Formale Bildung

"What is the highest level of education you have completed?"

**SD10** Formale Bildung

1 = Still in school \[1\]\
2 = Finished school with no qualifications \[2\]\
3 = Secondary school-leaving certificate/Junior High Diploma \[3\]\
4 = General Certificate of Secondary Education (GCSEs) \[4\]\
5 = \[5\]\
6 = Vocational secondary certification (completion of specialized
secondary school/college) \[6\]\
7 = A-levels/International Baccalaureate, subject-related higher
education entrance qualification \[7\]\
8 = University degree \[8\]\
9 = Other school-leaving qualification: \[9\]\
-9 = Not answered

<div class="items">

**SD10\_09** Other school-leaving qualification

Free text

</div>

</div>

<div class="question">

[\[SD11\]]{.ident} Selection

Formale Bildung (einfach)

"What is your highest educational achievement?"

**SD11** Formale Bildung (einfach)

1 = Finished school with no qualifications\
9 = Still in school\
3 = Secondary school-leaving certificate/Junior High Diploma\
4 = High school diploma/Intermediate/General Certificate of Secondary
Education, secondary school-leaving certificate or equivalent\
5 = Completed apprenticeship\
6 = Vocational baccalaureate diploma, vocational secondary
certification\
7 = A-levels/International Baccalaureate/Higher education entrance
qualification\
8 = Vocational university/university of applied sciences/university
degree\
10 = Other degree:\
-9 = Not answered

<div class="items">

**SD11\_10** Other degree

Free text

</div>

</div>

<div class="question">

[\[SD12\]]{.ident} Selection

Beruflicher Bildungsabschluss

"What professional qualifications do you have?"

**SD12** Beruflicher Bildungsabschluss

1 = No professional qualifications\
2 = Vocational training period with diploma\
3 = (Compact) vocational training program/course\
4 = Completed industrial or agricultural apprenticeship\
5 = Completed commerical traineeship\
6 = Internship, practical training\
7 = Specialized vocational qualification\
8 = General vocational qualification\
9 = Master/technical certification or equivalent vocational
qualification\
10 = Vocational university/university of applied sciences degree\
11 = University degree\
12 = Other degree:\
-9 = Not answered

<div class="items">

**SD12\_12** Other degree

Free text

</div>

</div>

<div class="question">

[\[SD13\]]{.ident} Selection

Erwerbstätigkeit

"Are you currently employed?"

**SD13** Erwerbstätigkeit

1 = Yes, I am employed.\
2 = No, I am unemployed.\
3 = No, I am retired.\
4 = No, I am a homemaker.\
5 = No, none of the above.\
-9 = Not answered

</div>

<div class="question">

[\[SD14\]]{.ident} Selection

Beschäftigung

"What do you do professionally?"

**SD14** Beschäftigung

1 = Pupil/in school\
2 = Training/apprenticeship\
3 = University student\
4 = Employee\
5 = Civil servant\
6 = Self-employed\
7 = Unemployed/seeking employment\
8 = Other:\
-9 = Not answered

<div class="items">

**SD14\_08** Other

Free text

</div>

</div>

<div class="question">

[\[SD15\]]{.ident} Text Input

Beschäftigung (offen)

"What are you working?"

<div class="items">

**SD15\_01** \[01\]

Free text

**SD15\_01a** \[01\]: I am still in school or training

1 = Not checked\
2 = Checked

</div>

</div>

<div class="question">

[\[SD16\]]{.ident} Dropdown Selection

Einkommen I

"What is your monthly net income?"

**SD16** Einkommen I

1 = I do not have a personal income\
2 = less than 250 €\
3 = 250 € up to 500 €\
4 = 500 € up to 1000 €\
5 = 1000 € up to 1500 €\
6 = 1500 € up to 2000 €\
7 = 2000 € up to 2500 €\
8 = 2500 € up to 3000 €\
9 = 3000 € up to 3500 €\
10 = 3500 € up to 4000 €\
11 = 4000 € or more\
12 = I do not wish to answer\
-9 = Not answered

</div>

<div class="question">

[\[SD17\]]{.ident} Dropdown Selection

Einkommen II

"What is your monthly net income?"

**SD17** Einkommen II

1 = less than 250 €\
2 = 250 € up to 500 €\
3 = 500 € up to 1000 €\
4 = 1000 € up to 1500 €\
5 = 1500 € up to 2000 €\
6 = 2000 € up to 3000 €\
7 = 3000 € up to 4000 €\
8 = 4000 € up to 5000 €\
9 = 5000 € or more\
10 = I do not wish to answer\
-9 = Not answered

</div>

<div class="question">

[\[SD18\]]{.ident} Text Input

Anmerkungen (offen)

"Would you like to comment this questionnaire, or would you like to add
information for us to better understa..."

<div class="items">

**SD18\_01** \[01\]

Free text

</div>

</div>

</div>
