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
- excessive self-defense - happens when actor exceeds the limits of self-defence out of confusion, fear or terror; class name: Excessive_Self_Defense;
- duress - differs from excessive self-defense by the lack of the Danger (Action) Change; calss name: Action_Under_Duress;
- mistake of justifying fact - an Action under the belief that there is some justifying fact; class name: Action_While_Under_Mistake_Of_Justifying_Fact;
- mistake of excusing fact - an Action under the belief that there is some excusing fact; class name: Action_While_Under_Mistake_Of_Excusing_Fact;
- mistake of law - an Action under the belief that there is no offence; class name: Action_While_Under_Mistake_Of_Law;
- insanity - an Action committed without understanding legal norms expressed in some way; class name: Action_While_Insane;
- diminished responsibility - an Action committed with partial understanding of legal norms expressed in some way; class name: Action_With_Diminished_Responsibility;
- superior orders - an Action of committing a crime under a superior order; calss name: Action_Under_Superior_Order.
