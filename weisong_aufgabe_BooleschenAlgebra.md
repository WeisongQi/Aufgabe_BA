# Hausaufgabe Gesetze der Booleschen Algebra

## Aufgabe 1 

> A ∨ (A ∧ B)  
>
>>> Wegen *Distriutivgesetz*
>
> = (A ∨ A) ∧ (A ∨ B)  
>
>>> Wegen *Idempotenzgesetz*   
>
> = A ∧ (A ∨ B)         
>
>>> Wegen *Absorptionsgesetz*
>
> = A                    

## Aufgabe 2

> ¬( A ∧ B ) ∨ A  
>
>>> Wegen *De-Morgansches Gesetz*
>
> = ¬A ∨ ¬B ∨ A  
>
>>> Wegen *Kommutativgesetz*
>
> = ¬A ∨ A ∨ ¬B
>
>>> Wegen *Negationsgesatz*
>
> = 1 ∨ ¬B
>
>>> Wegen *Kommutativgesatz und Null- und Einsgesetz*
>
> = 1

## Aufgabe 3

> (A ∨ B) ∧ (A ∨ ¬B)  
> 
>>> Wegen *Distributivgesetz*
>  
> = A ∨ ( B ∧ ¬B )  
>
>>> Wegen *Negationsgesatz*
>  
> = A ∨ 0
>
>>> Wegen *Identitätsgesetz*
>
> = A

## Aufgabe 4

> (A ∧ (B ∨ C)) ∨ (¬A ∧ (B ∨ C))
> 
>>> Wegen *Kommutativgesatz*
> 
> = ((B ∨ C) ∧ A) ∨ ((B ∨ C) ∧ ¬A )
>
>>> Wegen *Distributivgesetz*
>
> = (B ∨ C) ∧ (A ∨ ¬A)  
>
>>> Wegen *Negationsgesatz*
> 
> = (B ∨ C) ∧ 1
>
>>> Wegen *Identitätsgesetz*
>
> = B ∨ C

## Aufgabe 5

> (A ⊕ B) ∨ (A ∧ ¬B)
>
>>> Wegen *"ausschließende Oder" Definition A⊕B = (A∧¬B) ∨ (¬A∧B)*  
>
> = ((A ∧ ¬B) ∨ (¬A ∧ B )) ∨ (A ∧ ¬B) 
>
>>> Wegen *Kommutativgesetz*
>
> = (A ∧ ¬B) ∨ (A ∧ ¬B) ∨ (¬A ∧ B ) 
>
>>> Wegen *Idempotenzgesetz*
>
> = (A ∧ ¬B) ∨ (¬A ∧ B ) 

## Aufgabe 6

> ((A ⊕ B) ∧ C) ∨ (¬C ∧ (A ⇒ B))
>
>>> Wegen *A⊕B und A⇒B  Definitionen A⊕B=(A∧¬B)∨(¬A∧B) und A⇒B=¬A∨B*
>
> = (((A∧¬B)∨(¬A∧B)) ∧ C) ∨ (¬C ∧ (¬A ∨ B))
>
>>> Wegen *Distributivgesetz und Kommutativgesetz*
>
> = ( (C ∧(A∧¬B)) ∨ (C ∧ (¬A∧B))  ) ∨ (¬C ∧ (¬A ∨ B))
> 
>>> Wegen *Assoziativgesetz*
>
> = (C ∧(A∧¬B)) ∨ ((C ∧ (¬A∧B)) ∨ (¬C ∧ (¬A ∨ B)))
>
>>> Wegen *Distributivgesetz und Negationsgesetz und Identitätsgesetz*
>
> = (C ∧ A ∧ ¬B) ∨ (¬A ∨ B)