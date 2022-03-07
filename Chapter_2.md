# Security Models

Confidentiality
## Bell-LaPadula:
"No read-up", Star property principle (no write-down)
Format used for military

## Brewer-Nash:
Defined by controlling read and write access based on conflict of interest rules. 
The Chinese Wall model, separtates groups through use of a 'wall'

## Biba:
No write-up, which prevents unauthorized modification of data, ring policy- can read any object regardless of level, but lowers integrity if an item is written to. 

## Clark-Wilson Security Model:
Uses transcations as a basis for rules; two levels of integrity- constrained data items (CDIs), whic are subject to integrity controls, and unconstrained data items, which are not. 
Like a bank, uses IVP (integrity verification processes), and TPs (transformation processes). 
