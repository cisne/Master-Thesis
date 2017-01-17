# Master-Thesis


Eindhoven University of Technology
Department of Mathematics and Computer Science
Architecture of Information Systems Research Group

Master's Thesis

A Comparative Study for Process Mining
Approaches in a Real-life Environment

Graciëla E. Hoogendoorn

A thesis submitted in partial fulfillment of the requirements
for the degree of Master of Science in Business Information Systems

Examination Committee:
prof. dr. ir. H.A. Reijers
dr. ir. H. Eshuis
ir. E. González López de Murillas
ir. P. Vos (Experis Ciber)

Eindhoven, January 2017



ABSTRACT

This study compares three process mining approaches to complete a process mining project in real-life. 
The motivation for this comparison is driven by the manifestation of a new technique to
create event logs, namely through the extraction of redo logs of a Data Base Management System.

We successfully applied this new technique with PADAS (Process Aware Data Suite)  for the first time in a real-life environment. 
The resulting event log of the `redo log process mining approach' was also verified by comparing it to an event log extracted 
with traditional techniques (i.e. a query on several tables). We found that these two event logs are equivalent.

However, to fairly compare complete process mining approaches to address real-life process mining projects with each other, 
no existing methodology existed. As such, this work defined and proposes a comparison framework for process mining approaches 
in real-life environments. The comparison framework uses quantitative and qualitative metrics to assess the actual and perceived 
efficacy of the execution of a task with a particular method. Tasks are defined in a structured manner through the application of 
the Process Mining Project Methodology, i.e. PM\textsuperscript{2}.

Accordingly, we evaluated the comparison framework by applying it to a case study. In total, we compared three process mining 
approaches to complete a project in real-life. First, the traditional process mining approach, widely applied in academic environments. 
Second, the redo log process mining approach.
Third, the approach using the off-the-shelf software suite for process mining from Celonis, which targets business oriented users. 
As such, we applied each of these process mining approaches on the same process mining project. 
Simultaneously we adapted the comparison framework. 

Our findings do not clearly point to one overall best-performing process mining approach but indicate 
that the best process mining approach should be determined based on the context of the process mining project. 
The choice depends for example on, the process mining experience of the process mining team, 
the time that is available for the project, the structure of the database, and the desired output for the analysis.
