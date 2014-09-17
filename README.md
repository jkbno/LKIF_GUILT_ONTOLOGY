LKIF_GUILT_ONTOLOGY
===================

This is a modified version of the LKIF Extended ontology.
Changes were made to describe basic notions concerning legal guilt.

Guilt in the majority of common law countries and some of the civil law countries consists of:
- direct intent (purpose) - in LKIF both forms of the intent are under one class; in many jurisdictions there is no distinction between two forms of intent and if there is, oblique intent is not a premise for a more lenient punishment; this change in the ontology is of a minor importance; class name: Disallowed_Direct_Intention;
- oblique intent (knowledge) - class name: Disallowed_Oblique_Intention;
- recklessness - according to Model Penal Code a person acts recklessly when he/she consciously disregards a substantial and unjustifiable risk connected with his/her conduct; the risk must be of such a nature and degree that its disregard involves a gross deviation from the standard of conduct that a law-abiding person would observe in the actor's situation; Risk and Standard_Of_Conduct are disjoint classes and Risk is not bevieved by an agent; class name: Recklessness;
- negligence - definition of negligence is similar to recklessness except that person should be aware of the risk, so it is prohibited not to be unaware (not believe); class name: Negligence.

Guilt in the rest of civil law countries consists of (list is not complete and depends on the particular jurisdiction):
- excessive self-defence,
- duress,
- mistake of justifying fact,
- mistake of excusing fact,
- mistake of law,
- insanity,
- diminished responsibility,
- superior orders.
