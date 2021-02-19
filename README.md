# Causal-TimeBank

### Description

Causal-TimeBank is the TimeBank corpus taken from [TempEval-3 task](http://www.cs.york.ac.uk/semeval-2013/task1/index.php?id=data), which is part of TempEval-3 English training data: [TBAQ-cleaned](http://www.cs.york.ac.uk/semeval-2013/task1/data/uploads/datasets/tbaq-2013-03.zip), annotated with causal information. The annotation was performed using the [CAT tool](https://dh.fbk.eu/resources/cat-content-annotation-tool) (Bartalesi Lenzi et al., 2012), a web-based application with a plugin to import annotated data in CAT-XML format and add new information on top of it, in this case causal information. The CAT-XML task file for annotating causal information on top of TimeML data (using CAT tool) is available [here](https://github.com/paramitamirza/TimeML-CAT-Converter/blob/master/CAT_task_Causal-TimeML.xml) ([CAT User Manual](http://celct.fbk.eu:8080/CAT_WEB_APP/manual/CAT_Manual.pdf): How to Manage Annotation Tasks).

We provide [a tool to convert text annotated with TimeML into CAT-XML format](http://github.com/paramitamirza/TimeML-CAT-Converter), and vice versa, written in Python.

Note that we only consider gold annotated EVENTs, TIMEX3s, SIGNALs and TLINKs from the TimeBank corpus (as SLINKs and ALINKs are considered irrelevant in this task), and we put new information about causality in the form of C-SIGNALs and CLINKs annotation. More information about the causality annotation can be found in one of the papers in the references section.

Contained in the corpus are:

- 6,811 EVENTs (only instantiated events by MAKEINSTANCE tag of TimeML)
- 5,118 TLINKs (temporal links)
- 171 CSIGNALs (causal signals)
- 318 CLINKs (causal links)

Whenever making reference to this resource please cite one of the papers in the references section.

### References

**Paramita Mirza**, Rachele Sprugnoli, Sara Tonelli and Manuela Speranza. 2014. Annotating causality in the TempEval-3 corpus. In _Proceedings of the EACL 2014 Workshop on Computational Approaches to Causality in Language (CAtoCL)_, pages 10–19, Gothenburg, Sweden, April. Association for Computational Linguistics. [pdf](http://www.aclweb.org/anthology/W14-0702) [bib](http://aclweb.org/anthology//W/W14/W14-0702.bib)
**Paramita Mirza** and Sara Tonelli. 2014. An Analysis of Causality between Events and its Relation to Temporal Information. In _Proceedings of the 25th International Conference on Computational Linguistics_, Dublin, Ireland.

Contact us: 
paramita135[at]gmail.com
