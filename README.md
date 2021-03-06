# ALG-TruthTableAssignment

# Second hand in - Logic

## A) Using a programming language of your choice write an application that generates a truth table for a given input – for example what is the truth table for ~(~p AND q) AND (p AND q)

## B) Using the laws of equivalence provide 10 examples of simplifying statements using the laws.

For this task we have made up 10 examples of statements that we will simplify using the laws.

### 1. ~(p ∧ ~q) ∨ p

We start by applying DeMorgan's law:

~(p ∧ ~q) ∨ p ≡ ~p ∨ ~(~q) ∨ p

Applying the double negative law doesnt really matter, as we can see that we can actually just apply the negation law to finish the simplification:

~p ∨ q ∨ p ≡ **t**


### 2. ~(~p ∧ ~q) ∨ ~(~p ∨ q) ∨ **t**

For this we can simply use the universal bound laws to see that this is just a tautology:

~(~p ∧ ~q) ∨ ~(~p ∨ q) ∨ **t** ≡ **t**

### 3. p ∨ (t ∨ ~q)

Similar to the one above, we first use the universal bound laws to isolate the tautology:

p ∧ (**t** ∨ ~q) ≡ p ∧ **t**

Now we can use the Identity law to remove the tautology from the statement:

p ∧ **t** ≡ p

### 4. (p ∨ (p ∧ q)) ∧ p

Here we first use the absorption laws:

(p ∨ (p ∧ q)) ∧ p ≡ p ∧ p

With this statement we can use the idempotent laws to isolate p:

p ∧ p ≡ p

### 5. (~(p ∧ ~q) ∨ ~(~p ∨ q)) ∧ ~**t**

First we have the negation of a tautology; a contradiction.

(~(p ∧ ~q) ∨ ~(~p ∨ q)) ∧ ~**t** ≡ (~(p ∧ ~q) ∨ ~(~p ∨ q)) ∧ **c**

We can now see, as in the same as #2, we can use the universal bound laws to isolate the contradiction:

(~(p ∧ ~q) ∨ ~(~p ∨ q)) ∧ **c** ≡ **c**

### 6. ~p ∨ (p ∧ (p ∨ ~p))

We start by using the negation laws:

~p ∨ (p ∧ (p ∨ ~p)) ≡ ~p ∨ (p ∧ **t**)

We now use the identity law to isolate p inside the parentethese:

~p ∨ (p ∧ **t**) ≡ ~p ∨ p

And finally we use the negation laws once again:

~p ∨ p ≡ **t**

### 7. p ∧ (q ∨ ~p)

First we use the distributive laws:

p ∧ (q ∨ ~p) ≡ (p ∧ q) ∨ (p ∧ ~p)

We can now use the universal bound laws:

(p ∧ q) ∨ (p ∧ ~p) ≡ (p ∧ q) ∨ **c**

And finally we can use the identity laws:

(p ∧ q) ∨ **c** ≡ p ∧ q

### 8. ∼(p ∨ t)

We first use De Morgan's law:

∼(p ∨ t) ≡ ∼p ∧ **∼t**

We then use the negation of a tautology:

∼p ∧ **∼t** ≡ ∼p ∧ **c**

To which we then can use the universal bound laws:

∼p ∧ **c** ≡ **c**

### 9. ∼(~p ∧ q) ∨ ~(p ∨ (p ∧ q))

We first start by using De Morgan's law:

∼(~p ∧ q) ∧ ~(p ∨ (p ∧ q)) ≡ (~(∼p) ∨ ∼q) ∧ ~(p ∨ (p ∧ q))

We then use the double negative laws aswell as the absorption laws:

(~(∼p) ∨ ∼q) ∧ ~(p ∨ (p ∧ q)) ≡ (p ∨ ∼q) ∧ ~p

We can then use the distributive law:

(p ∨ ∼q) ∧ ~p ≡ (~p ∧ ~q) ∨ (~p ∧ p)

Then we use the negation laws:

(~p ∧ ~q) ∨ (~p ∧ p) ≡ (~p ∧ ~q) ∨ **c**

To which we finally use the identity laws:

(~p ∧ ~q) ∨ **c** ≡ ~p ∧ ~q

### 10. ~(~p) ∧ (p ∧ (p ∨ ~p)

We start by using the negation laws aswell as double negative: 

~(~p) ∧ (p (p ∨ ~p) ≡ p ∧ (p ∧ **t**)

We then use identity laws:

p ∧ (p ∧ **t**) ≡ p ∧ p

And then we use the idempotent laws:

p ∧ p ≡ p

