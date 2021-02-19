# Causal-TimeBank

##Description

Causal-TimeBank is the TimeBank corpus taken from TempEval-3 task, which is part of TempEval-3 English training data: TBAQ-cleaned, annotated with causal information. The annotation was performed using the CAT tool (Bartalesi Lenzi et al., 2012), a web-based application with a plugin to import annotated data in CAT-XML format and add new information on top of it, in this case causal information. The CAT-XML task file for annotating causal information on top of TimeML data (using CAT tool) is available here [CAT User Manual: How to Manage Annotation Tasks].

We provide a tool to convert text annotated with TimeML into CAT-XML format, and vice versa, written in Python.

Note that we only consider gold annotated EVENTs, TIMEX3s, SIGNALs and TLINKs from the TimeBank corpus (as SLINKs and ALINKs are considered irrelevant in this task), and we put new information about causality in the form of C-SIGNALs and CLINKs annotation. More information about the causality annotation can be found in one of the papers in the references section.

Contained in the corpus are:

6,811 EVENTs (only instantiated events by MAKEINSTANCE tag of TimeML)
5,118 TLINKs (temporal links)
171 CSIGNALs (causal signals)
318 CLINKs (causal links)
