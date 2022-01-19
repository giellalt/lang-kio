
INTRODUCTION TO MORPHOLOGICAL ANALYSER OF Kiowa LANGUAGE.


# Definitions for Multichar_Symbols

## Analysis symbols
The morphological analyses of wordforms for the Kiowa
language are presented in this system in terms of the following symbols.
(It is highly suggested to follow existing standards when adding new tags).


POS

* +N	        
* +V	        
* +Prop	        
* +Adv        
* +CC	        
* +CS	        
* +Interj     
* +Pron       
* +Num        
* +Arab        
* +Rom        
* +PUNCT       = punctuation symbols
* +LEFT        = the left part of a paired punctuation symbol
* +RIGHT       = the right part of a paired punctuation symbol
* +CLB         = clause boundary symbols
* +Symbol = independent symbols in the text stream, like £, €, ©

* +Loc         Locative

* +Dim      Diminutive

 * +Ipc		 Indeclinable Particle

* +Dem         Demonstrative
* +Def	     This is the intransitive demonstrative, i.e. the definite.
* +Prox	     Demonstrative Proximate
* +Med	     Demonstrative Medial
* +Dist	     Demonstrative Distal

* +Foc	     Focus particle

Verbal MSP
* +Prs  
* +Fut  
* +Prt  
* +Prf  
* +Cnj  
* +Int   This tag is for the Future Intentional
* +Def   This tag is for the Future Definite

* +Ind   Indicative, aka Independent
* +Imp   Imperative, consider deleting +Imp tag
* +Del   Delayed imperative
* +Imm   Immediate imperative, consider deleting +Imp tag
* +Sbj   Subjunctive, aka Conjunct mode, ê-
* +Cond  TODO: Should Future Conditional be tagget Fut only? Conor: we will split the Future tags




* +1Sg     first singular
* +2Sg     etc
* +2Sg/Pl    Used in the syncretic 2sg/pl -> 1pl in the VTA paradigms
* +3Sg    

* +1Pl     1Pl is exclusive plural (I, them, not you)
* +2Pl    
* +3Pl    
* +12Pl    12Pl is inclusive plural (I, you, ...)
* +4Sg     Fourth Person inanimate singlar (used only in the VII paradigms)
* +4Pl     Fourth Person inanimate plural (used only in the VII paradigms)
* +4Sg/Pl    
* +5Sg/Pl    

* +1SgO    objective conjugation
* +2SgO   
* +2Sg/PlO    Used in the syncretic 2sg/pl -> 1pl in the VTA paradigms
* +3SgO   
* +SgO    
* +1PlO   
* +2PlO   
* +3PlO   
* +PlO    
* +4Sg/PlO  ambiguous 4th person (both Singular and Plural)
* +5Sg/PlO  ambiguous 5th person (both Singular and Plural)
* +X  Unspecified actor forms Okimāsis p. 118


Nominal MSP
* +Sg		  singular
* +Pl		  plural

* +Px1Sg	  person prefixes for nouns
* +Px2Sg	 
* +Px3Sg	 
* +Px4Sg	 
* +Px1Pl	  obviative
* +Px12Pl	  inclusive
* +Px2Pl	 
* +Px3Pl	 
* +Px4Pl	 
* +Der/Dim  diminutive derivation

* RdplW+  Reduplication Type 1 (Weak)
* RdplS+  Reduplication Type 2 (Strong)

* +Der/Com  Comitative circumfix (wîci-...-m)
* +Der/X  VTI x-actor to VII-1

Verb conjugation (transitivity + animacy classes)
* +AI       intransitive with animate subject,
* +II       intransitive with inanimate subject,
* +TA       transitive with animate object, and
* +TI       transitive with inanimate object.

Noun animacy and dependency classes
* +A		  animate noun
* +I		  inanimate noun
* +D		  dependent noun

* +Incl     me too, etc.
* +Qst      yes-no question particle ci

The Usage extents are marked using following tags:



## Flag diacritics


|  @U.person.1Sg@     | IV person tags
|  @U.person.2Sg@     | IV person tags
|  @U.person.3Sg@     | IV person tags
|  @U.person.4Sg@     | IV person tags
|  @U.person.1Du@     | IV person tags
|  @U.person.2Du@     | IV person tags
|  @U.person.3Du@     | IV person tags
|  @U.person.4Du@     | IV person tags
|  @U.person.1Pl@     | IV person tags
|  @U.person.2Pl@     | IV person tags
|  @U.person.3Pl@     | IV person tags
|  @U.person.4Pl@     | IV person tags


|  @U.person.1SgOSg@     | TV person flags
|  @U.person.1SgODu@     | TV person flags
|  @U.person.1SgOPl@     | TV person flags
|  @U.person.1SgOIn@     | TV person flags

|  @U.person.2SgOSg@     | TV person flags
|  @U.person.2SgODu@     | TV person flags
|  @U.person.2SgOPl@     | TV person flags
|  @U.person.2SgOIn@     | TV person flags

|  @U.person.3SgOSg@     | TV person flags
|  @U.person.3SgODu@     | TV person flags
|  @U.person.3SgOPl@     | TV person flags
|  @U.person.3SgOIn@     | TV person flags

|  @U.person.1DuOSg@     | TV person flags
|  @U.person.1DuODu@     | TV person flags
|  @U.person.1DuOPl@     | TV person flags

|  @U.person.2DuOSg@     | TV person flags
|  @U.person.2DuODu@     | TV person flags
|  @U.person.2DuOPl@     | TV person flags
|  @U.person.2DuOIn@     | TV person flags

|  @U.person.3DuOSg@     | TV person flags
|  @U.person.3DuODu@     | TV person flags
|  @U.person.3DuOPl@     | TV person flags
|  @U.person.3DuOIn@     | TV person flags

|  @U.person.2PlOSg@     | TV person flags
|  @U.person.2PlODu@     | TV person flags
|  @U.person.2PlOPl@     | TV person flags
|  @U.person.2PlOIn@     | TV person flags

|  @U.person.3PlOSg@     | TV person flags
|  @U.person.3PlODu@     | TV person flags
|  @U.person.3PlOPl@     | TV person flags

|  @U.person.4PlOSg@     | TV person flags
|  @U.person.4PlODu@     | TV person flags
|  @U.person.4PlOPl@     | TV person flags


### crk flags
We have manually optimised the structure of our lexicon using following
flag diacritics to restrict morhpological combinatorics - only allow compounds
with verbs if the verb is further derived into a noun again:
|  @P.NeedNoun.ON@ | (Dis)allow compounds with verbs unless nominalised
|  @D.NeedNoun.ON@ | (Dis)allow compounds with verbs unless nominalised
|  @C.NeedNoun@ | (Dis)allow compounds with verbs unless nominalised

For languages that allow compounding, the following flag diacritics are needed
to control position-based compounding restrictions for nominals. Their use is
handled automatically if combined with +CmpN/xxx tags. If not used, they will
do no harm.
|  @P.CmpFrst.FALSE@ | Require that words tagged as such only appear first
|  @D.CmpPref.TRUE@ | Block such words from entering ENDLEX
|  @P.CmpPref.FALSE@ | Block these words from making further compounds
|  @D.CmpLast.TRUE@ | Block such words from entering R
|  @D.CmpNone.TRUE@ | Combines with the next tag to prohibit compounding
|  @U.CmpNone.FALSE@ | Combines with the prev tag to prohibit compounding
|  @P.CmpOnly.TRUE@ | Sets a flag to indicate that the word has passed R
|  @D.CmpOnly.FALSE@ | Disallow words coming directly from root.

Use the following flag diacritics to control downcasing of derived proper
nouns (e.g. Finnish Pariisi -> pariisilainen). See e.g. North Sámi for how to use
these flags. There exists a ready-made regex that will do the actual down-casing
given the proper use of these flags.
|  @U.Cap.Obl@ | Allowing downcasing of derived names: deatnulasj.
|  @U.Cap.Opt@ | Allowing downcasing of derived names: deatnulasj.

The word forms in Kiowa language start from the lexeme roots of basic
word classes, or optionally from prefixes:

* * *
<small>This (part of) documentation was generated from [../src/fst/root.lexc](http://github.com/giellalt/lang-kio/blob/main/../src/fst/root.lexc)</small>