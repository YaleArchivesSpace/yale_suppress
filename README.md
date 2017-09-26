# yale_suppress
Local plugin that suppresses fields from the staff interface that are not used at Yale. Also changes the default display for 
Collection Management subrecords in the read-only view of accession records, expanding the accordion intead of collapse.

The following records and subrecords have the listed fields suppressed in the view and edit modes for the relevant record types:

###ACCESSIONS  

resource_type   
restrictions_apply

###DATES  

certainty  
era  
calendar  

###LINKED AGENTS  

title [For Linked Agents with Role = Creator - Only suppressed in edit mode]

###USER DEFINED  

boolean_3 [Suppressed in edit mode only - will still appear in view mode]  
integer_1  
integer_2  
integer_3  
real_2  
real_3  
date_3  
enum_3  
eum_4  

###RESOURCES  

restrictions

###ARCHIVAL OBJECTS

restrictions_apply
