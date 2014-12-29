```
aand 191                                      =apply 267
abbrev 214                                    arch
abbrevs 214                                      Lisp as 8
abbreviations 213                                bottom-up program as 4
Abelson, Harold 18                            architects 284
Abelson, Julie 18                             Armstrong, Louis vii
ablock 193                                    artiﬁcial intelligence 1
Abrahams, Paul W. 391                         asetf 223
:accessor 365                                 assignment
accumulators 23, 47, 394                         macros for 170
acond 191                                        order of 177
acond2 198, 239                                  parallel 96
Adams, Norman I. 396                             in Prolog 343
after 50                                         and referential transparency 198
aif 191                                          see also: generalized variables
aif2 198                                      assoc 196
alambda 193                                   ATNs 305
Algol 8                                          arc types 311
allf 169                                         correctness of 312
:allocation 367                                  destructive operations in 313
always 227                                       like functional programs 316
alrec 205                                        for natural language 305
anaphora—see macros, anaphoric                   nondeterminism in 308
ANSI Common Lisp ix                              operations on register stack 398
antecedent 322                                   order of arcs 308
append                                           recursion in 306
   Prolog implementation 331                     registers of 306, 312
append1 45                                       represented as functions 309
apply 13                                         tracing 309
   with macros 110                            atrec 210
   on &rest parameters 137                    augmented transition networks—see ATNs

---

Autocad 1, 5                                      call-next-method 200, 375
automata theory 292                                  sketch of 358
avg 182                                           call-with-current-continuation
awhen 191                                                  (call/cc) 260
awhen2 198                                           at toplevel 292
awhile 191                                        capital expenditures 43
awhile2 198                                       capture 118
                                                     avoiding with gensyms 128
backtraces 111                                       avoiding with packages 130
backtracking 292                                     avoiding by prior evaluation 125
backquote (‘) 84                                     of block names 131
   in ATNs 307                                       detecting potential 121
   nested 214, 217, 395                              free symbol capture 119
bad-reverse 29                                           avoiding 125
barbarians 283                                       of function names 131, 392
Basic 30, 33                                         intentional 190, 267, 313
battleﬁeld 8                                         macro argument capture 118
before 50                                            of tags 131
Benson, Eric 137                                  case 15
best 52                                           >case 152
Bezier curves 185                                 case-sensitivity 331
=bind 267                                         chains of closures 76, 269
binding 239                                       Chocoblobs 298
binding lists 239                                 choose 287
bindings, altering 107                               extent of 291
blackboards 281                                   choose
block 154                                            Common Lisp version 295
   implicit 131, 155                                 Scheme version 293
block-names 131                                   choose-bind 295
body (of expressions) 87, 91, 87                  chronological backtracking 292
body (of a rule) 322                              classes
&body 87                                             deﬁning 364
bookshops 41                                         see also: superclasses
bottom-up design v, 3, 321                        Clinger, William 395
   and functional arguments 42                    CLOS 364

   and incremental testing 38                        as an embedded language 349, 377
   and shape of programs 4                           see also: classes, generic functions,
   multilayer 321                                          methods, slots
bound—see variables, bound                        closed world assumption 249
break-loop 56                                     closures 17, 62, 76
brevity viii, 43                                  CLTL—see Common Lisp: the Language

bricks, furniture made of 117                     code-walkers 237, 273
Brooks, Frederick P. 5                            Common Lisp: the Language ix
                                                  Common Lisp
                                                     case-sensitivity of 331
C 388                                                deﬁnition of ix
C++ 398

---

  differences between versions                      complement 62
     compilation of closures 25                     compose 66
     complement 62                                  composition—see functions,
     defpackage 384                                          composition of
     destructuring-bind 93                          conc1 45
     dynamic-extent 150                             conc1f 170, 174
     environment of expanders 96, 393               concf 170
     no expansion in compiled code 136              concnew 170
     function-lambda-expression 390                 conditionals 108, 150
     *gensym-counter* 129                           condlet 146
     -if-not deprecated 62                          congruent parameter lists 372
     ignore-errors 147                              consequent 322
     inversions from defun 179                      consing
     Lisp package 384                                  avoiding 31, 150, 197, 363
     name of user package 381                       constitutional amendments 391
     redeﬁning built-in operators 131,              constraints 332
        199                                         *cont* 266
     &rest parameters not fresh 137                 context
     symbol-macros 205                                 and referential transparency 199
     with-slots 236                                    see also: environments; macros,
     see also: CLOS, series                                  context-creating
  evaluation rule 392                               continuations 258
  long names in 393                                    destructive operations in 261, 313
  vs. Scheme 259                                       cost of 284
Common Lisp Object System—see CLOS                     see also: call-with-current-con-
common-lisp 384                                              tinuation
common-lisp-user 381                                continuation-passing macros 266
compall 388                                            use in multiprocessing 283
compilation 24                                         use in nondeterministic choice 296
  bounds-checking during 186                           restrictions on 270
  computation during 109, 181, 197,                    and tail-recursion optimization 298
        254, 335                                    continuation-passing style (CPS) 273
  of embedded languages 116, 254                    cookies 184
  errors emerging during 139                        copy-list 71, 206
  inline 26, 109, 110                               copy-tree 71, 210
     testing 388                                    courtiers 375
  of local functions 23, 25, 81, 346                cut 337
  of macro calls 83, 101, 136                          with fail 342
  of networks 79                                       green 339
  restrictions on 25                                   red 339
  senses of 346                                        in Lisp 298
  of queries 254                                    cut 301
  see also: tail-recursion optimization
compile 24, 116, 388                                databases
compile-file 25                                        caching updates to 179
compiled-function-p 24                                 locks on 148

---

   natural language interfaces to 306                    generalization of 156
   queries on 246                                      Dolphin Seafood 219
   representation of 247                               dotted lists 70, 390
   with Prolog 398                                     duplicate 50
dbind 232                                              dynamic extent 127, 150
def! 64                                                dynamic languages 398
defanaph 223                                           dynamic scope 16
defclass 364
defdelim 228                                           Edwards, Daniel J. 391
defgeneric 371                                         elt 244
define-modify-macro 168                                Emacs—see Gnu Emacs
defmacro 82, 95                                        embedded languages 7, 188, 246
defpackage 384                                            ATNs as 309
defprop 354                                               beneﬁts of 110,116, 246, 377
defun 10, 113                                             borderline of 246
   deﬁning inversions with 179                            compilation of 116
=defun 267                                                not quite compilers 346
defsetf 178                                               implementation of 116
delay 211                                                 for multiprocessing 275
delete-if 64                                              Prolog as 321
density of source code 59, 389                            query languages as 246
destruc 232                                               see also: CLOS
destructive operations 31, 64                          end-of-ﬁle (eof) 197, 225
destructuring                                          English 306
   on arrays 234                                       environment
   on instances 236                                       argument 95
   on lists 230                                           interactive 8
   in macros 93                                           of macro expanders 96, 393
   and reference 236                                      of macro expansions 108
   on sequences 231                                       null 96, 278, 394
   on structures 235                                   error 148
destructuring-bind 93, 213, 230                        error-checking 45
differences 207                                        eval
disassemble 388                                           explicit 34, 163, 197, 278
dispatching 370, 371                                      on macroexpansions 92
do 98                                                     sketch of 391
   implicit block in 131                               evaluation
   multiple-valued version 162                            avoiding 151, 181
   order of evaluation in 392                             lazy 211
do-file 199                                               order of
do-symbols 388, 393                                          in Common Lisp 135
do-tuples/c 156                                              in Scheme 259
do-tuples/o 156                                           sketch of 391
do* 97                                                 evaluation rule 392
   multiple-valued version 159                         evenp 14
dolist 94                                              evolution

---

   design by 1                                          funcall 13, 259
   of Lisp 158                                          =funcall 267
   of programming languages 8                           function calls, avoiding
expander code 99                                           by inline compilation 26
expansion code 99                                          with macros 109
explode 58                                                 by tail recursion 23
exploratory programming 1, 284                          functional interfaces 35
export 383                                              functional programs 28
:export 384                                                almost 35
expt 32                                                    and bottom-up programming 37
extensibility 5                                            from imperative ones 33
   of object-oriented programs 16, 379                     shape of 30
extent, dynamic 127, 150                                functions
                                                           as arguments 13, 42, 177
 f 173, 222                                                constant 226
factions 167                                               closures of 17, 62, 76
factorials 343, 387                                            use in nondeterministic choice 296
fail 287                                                       stack allocation of 150
fail                                                       combined with macros 141, 149, 266
   Common Lisp version 295                                 compiled 24
   Scheme version 293                                      composition of 66, 201, 228
failure 195                                                as a data type 9
fboundp 388                                                deﬁning 10
fif 67                                                     ﬁlleting 115
filter 47                                                  generating recursive 68, 204
   simpler version 389                                     generic—see generic functions
find2 50                                                   internal 172
   evolution of 41                                         interpreted 24
find-if 41, 195                                            as lists 27
   sketch of 206                                           literal 11
   version for trees 73                                        recursive 21, 193
ﬁnished programs 285                                       local 21
fint 67                                                    vs. macros 109
flatten 47, 72, 210                                        names of 11, 213
   simpler version 389                                     as properties 15
Floyd, Robert W. 293                                       redeﬁning built-in 131, 174
fmakunbound 373                                            as return values 17, 61, 76, 201
fn 202, 229                                                set operations on 67, 201
Foderaro, John K. v                                        with state 18, 65
for 154                                                    tail-recursive 23
force 211                                                  transforming into macros 102
Fortran 8                                                  undeﬁning 373
free—see variables, free                                   see also: compilation; defgeneric;
fullbind 324                                                      defun; labels
fun x                                                   function-lambda-expression 390
fun 67

---

Gabriel, Richard P. 23                                  incf 171
garbage                                                    generalization of 173
   avoiding—see consing, avoiding                       incremental testing 37
   collection 8, 81                                     indexing 249
generalized variables 107, 165                          inheritance
   meaning of 179                                          single 196
   see also: inversions                                    of slots 366
generic functions 371                                      multiple 366
   deﬁning 371                                                 sketch of 351
   removing 373                                         in-if 152
   see also: methods                                    :initarg 365
gensym 128                                              :initform 365
   to indicate failure 197                              in-package 382
   as unbound 244, 330                                  inq 152
gensym? 243                                             instances 365
*gensym-counter* 129                                    intellectuals 374
gentemp 392                                             interactive development 37, 316
Gelernter, David H. 198                                 interactive environment 8
get 63                                                  intercourse, lexical 108
gethash 196                                             Interleaf 1, 5
   recursive version 350                                intern 128, 136, 266
get-setf-method 171                                     interning 128, 136, 381
gift-shops, airport 278                                 intersection 207
Gnu Emacs 1, 5                                          intersections 207
go 100, 155                                             inversions
gods 8                                                     asymmetric 179
gold 386                                                   deﬁning 178
good-reverse 30                                            see also: generalized variables
group 47                                                iteration
   simpler version 389                                     macros for 108, 154
                                                           vs. nondeterministic choice 291, 325
Hart, Timothy P. 391                                       without loops 264, 325
hash tables 65, 247, 350
head 322                                                Jagannathan, Suresh 198
hiding implementation details 216, 382                  jazz vii
hygienic macros 392                                     joiner 62
                                                        joke, practical—see Nitzberg, Mark
ice-cream 370
ice-skating 33                                          keywords 386
if3 150
if-match 242                                            labels 21
ignore-errors 147                                       lambda 11
Igor 289                                                =lambda 267
imperative programming 33                               lambda-expressions 11, 21
import 383                                              last 45
in 152                                                  last1 45

---

Latin 306                                                  macro-characters—see read-macros
lawyers 298                                                macros 82
let 144, 199                                                 as abbreviations 213
let* 172                                                     access 167, 216
lengths of programs 387                                      anaphoric 189
Levin, Michael I. 391                                           deﬁning automatically 218
lexical scope 16                                                for distinguishing failure from fal-
life, meaning of 197                                                sity 195
lions 37                                                        for generating recursive functions
Lisp                                                                204
    1.5 95                                                      multiple-valued 198
    deﬁning features of 1, 8, 349, 398                          and referential transparency 198
    integration with user programs 110                          see also: call-next-method
    slowness of 285                                          and apply 110
    speed of 388                                             applications of 111
    see also Common Lisp, Scheme, T                          arguments to 107
lists                                                        for building functions 201
    accumulating 47                                          calls invertible 166, 216
    as binary trees 70                                       clarity 99, 233
    as code 116                                              and CLOS 378
    decreased role of 44                                     for computation at compile-time 181
    disambiguating return values with 196                    context-creating 143
    dotted 390                                               combined with functions 141, 149,
    as facts 247                                                    266
    ﬂat—see flatten                                          compiled 83, 101, 136
    interleaving 160                                         complex 96
    operating on end of 170                                  deﬁning 82
    quoted 37                                                efﬁciency 99
    recursers on 68, 204                                     environment argument to 95
    as trees 262                                             environment of expander 96, 393
    uses for 70                                              environment of expansion 108
list processing 44, 398                                      errors in
locality 36                                                     modifying arguments 137
logic programs 334                                              modifying expansions 139
longer 47                                                       non-functional expanders 136
    simpler version 389                                         nonterminating expansion 139
loop 154                                                        number of evaluations 133, 167
loops                                                           order of evaluation 135
    interrupting 154                                            see also: capture
    see also: iteration                                      expansion of 83
lrec 69                                                         in compiled code 136
                                                                multiple 136, 138
McCarthy, John 1, 391                                           non-terminating 139
mac 92                                                          testing 92
macroexpand 91                                                  time of 83
macroexpand-1 91                                             from functions 102

---

  vs. functions 109                                misuse of 151
  hygienic 392                                     Prolog implementation 332
  justiﬁcation of 392                              returns a cdr 50
  macro-deﬁning 213, 266                         Miller, Molly M. 137
  parameter lists 93                             member-if 196
  position in source code 102, 266               memq 88
  as programs 96                                 memoizing 65, 174
  proportion in a program 117                    message-passing 350
  recursion in 139                                 vs. Lisp syntax 353
  redeﬁning 101, 138                             methods
     built-in 199                                  adhere to one another 369
  simple 88                                        after- 374
  skeletons of 121                                    sketch of 357
  style for 99                                     around- 375
  testing 91                                          sketch of 356
  unique powers of 106                             auxiliary 374
  when to use 106                                     sketch of 356
  see also: backquote, read-macros,                before- 374
        symbol-macros                                 sketch of 357
mainframes 348                                     of classes 368
make-dispatch-macro-character 226                  without classes 371
make-instance 365                                  as closures 378
make-hash-table 65                                 redeﬁning 372
make-string 58                                     removing 373
map-> 54                                              sketch of 359
map0-n 54                                          isomorphic to slots 368
map1-n 54                                          specialization of 369
mapa-b 54, 228                                        on objects 371
mapc 163                                              on types 370
mapcan 41, 46                                      see also: generic functions
  nondestructive version 55                      method combination
  sketch of 55                                     and
mapcar 13                                             sketch of 363
  version for multiple lists 55                    operator 376
  version for trees 55                                sketch of 362
mapcars 54                                         or
mapcon 176, 218                                       sketch of 363
mappend 54                                         progn
mappend-mklist idiom 160                              sketch of 362
mapping functions 53                               standard 376
mark 301                                              sketch of 358
match 239                                        :method-combination 377
matching—see pattern-matching                    Michelangelo 11
maxmin 207                                       mines 264
Meehan, James R. 396                             mklist 45, 160
member 88                                        mkstr 58

---

modularity 167, 381, 382                                      restrictions on 297
de Montaigne, Michel 2                                        and tail-recursion optimization 298,
most 52                                                           396
most-of 182                                                Scheme implementation 293
mostn 52                                                   appearance of foresight 289
moving parts 4                                             breadth-ﬁrst 303
multiple inheritance—see inheritance,                      correct 302
          multiple                                         depth-ﬁrst 292
multiple values 32                                            in ATNs 308
   to avoid side-effects 32                                   nonterminating 293
   to distinguish failure from falsity 196,                   in Prolog 334
          239                                              in functional programs 286
   in generalized variables 172                            vs. iteration 291, 325
   iteration with 158                                      optimizing 298
   receiving—see multiple-value-bind                       and parsing—see ATNs
   returning—see values                                    and search 290
multiple-value-bind 32                                     see also: choose, fail
   leftover parameters nil 234                           Norvig, Peter 199
multiprocessing 275                                      nreverse 31
mvdo 162                                                   sketch of 388
mvdo* 159                                                nthmost 183
mvpsetq 161
Mythical Man-Month, The 5                                object-oriented programming
                                                            dangers of 379
name-spaces 12, 205, 259, 273, 384, 392                     deﬁning features of 350
natural language—see ATNs                                   like distributed systems 348
nconc 31, 35, 137                                           and extensibility 16, 379
negation                                                    name of 349
   of facts 249                                             in plain Lisp 349
   in Prolog 325                                            see also: C++; classes; CLOS; generic
   in queries 252                                                 functions; inheritance; methods;
networks                                                          message-passing; slots; Smalltalk
   representing 76, 79                                   on-cdrs 205
next-method-p 375                                        on-trees 210
   sketch of 358                                         open systems 6
:nicknames 384                                           open-coding—see compilation, inline
nif 150                                                  orthogonality 63
nil
   default block name 131                                *package* 125, 381
   forbidden in case clauses 153                         packages 381
   multiple roles of 51, 195                               aberrations involving 384
nilf 169                                                   avoiding capture with 130, 131
Nitzberg, Mark—see joke, practical                         creating 382
nondeterministic choice 286                                current 381
   Common Lisp implementation 295                          using distinct 131, 382
      need for CPS macros 296                              inheriting symbols from 384

---

   nicknames for 384                                           order of 329
   switching 382                                            subverting 346
   user 381                                                 syntax of 331
   see also: intern; interning                           promises 211
parsers, nondeterministic—see ATNs                       prompt 56
paths, traversing 155                                    property lists 15, 63, 216
pat-match 242                                            propmacro 216
pattern-matching 186, 238                                   alternative deﬁnition 393
pattern variables 238                                    propmacros 216
phrenology 30                                            prune 47
planning 2                                                  simpler version 389
pointers 76                                              pruning search trees—see cut
pools 313                                                psetq 96
popn 173                                                    multiple-valued version 161
pop-symbol 220                                           pull 173, 223
position 49                                              pull-if 173
*print-array* 245                                        push-nreverse idiom 47
*print-circle* 70                                        pushnew 174
print-names 57, 129, 382
processes 275                                            queries
   instantiation of 278                                    complex 249, 335
   scheduling of 279                                       conditional 191
   state of 278                                          query languages 249
proclaim 23, 45                                          quicksort 345
productivity 5                                           quote 84, 391
programming languages                                      see also: ’
   battleﬁeld of 8                                       quoted lists, returning 37, 139
   embedded—see embedded languages
   expressive power of vii
   extensible 5                                          rapid prototyping 1, 284
   high-level 8                                             of individual functions 24, 48
   see also: Algol; Basic; C; C++; Com-                  read 56, 128, 197, 224
         mon Lisp; Fortran; Lisp; Pro-                   read-delimited-list 227
         log; Scheme; Smalltalk; T                       :reader 367
Prolog 321                                               read-eval-print loop 57
   assignment in 343                                     read-from-string 58
   calling Lisp from 343                                 read-line 56
   case-sensitivity of 331                               readlist 56
   conceptual ingredients 321                            read-macros 224
   nondeterminism in 333                                 recurser 388
   programming techniques 332                            recursion
   restrictions on variables 344                            on cdrs 68, 204
   rules 329                                                in grammars 306
      bodyless 323, 330                                     in macros 139, 192
      implicit conjunction in body 328                      without naming 388
      left-recursive 334                                    on subtrees 70, 208
                                                            tail- 23, 140

---

reduce 207, 363                                           setf 165
Rees, Jonathan A. 395, 396                                   see also: generalized variables, inver-
referential transparency 198                                        sions
remove-duplicates                                         set-macro-character 224
   sketch of 206                                          setq
remove-if 14                                                 destroys referential transparency 198
remove-if-not 40                                             ok in expansions 100
rep 324                                                      now redundant 170
reread 58                                                 Shapiro, Ehud 398
&rest parameters 87                                       sharp (#) 226
   not guaranteed fresh 137                               shuffle 161
   in utilities 174                                       side-effects 28
return 131, 155                                              destroy locality 36
return-from 131, 154                                         in macro expanders 136
return values                                                mitigating 35
   functions as—see functions, as retur       n              on &rest parameters 137
         values                                              on quoted objects 37
   multiple—see multiple values                           signum 86
re-use of software 4                                      simple? 242
reverse 30                                                single 45
rfind-if 73, 210                                          Sistine Chapel 11
   alternate version 390                                  skeletons—see macros, skeletons of
rget 351                                                  sketches 284
rich countries 285                                        sleep 65
rmapcar 54                                                slots
Rome 283                                                     accessor functions for 365
rotatef 29                                                   declaring 364
rplaca 166                                                   as global variables 379
rules                                                        initializing 365
   structure of 322                                          isomorphic to methods 368
   as virtual facts 323                                      read-only 367
   see also: Prolog, rules in                                shared 367
                                                          Smalltalk 350
Scheme                                                    some
   vs. Common Lisp 259                                       sketch of 206
   cond 192                                               sort 14, 352
   macros in 392                                          sortf 176
   returning functions in 62                              sorting
scope 16, 62                                                 of arguments 176
scoundrels, patriotic 352                                    partial 184
scrod 219                                                    see also: stable-sort
search trees 265                                          special 17
sequence operators 244                                    special forms 9, 391
series 55                                                 specialization—see methods, specializa-
set 178                                                             tion of
set-difference 207                                        speed 23

---

splicing 86                                               tagbody 155
splines—see Bezier curves                                 tail-recursion optimization 22
split-if 50                                                  needed with CPS macros 298
sqrt 32                                                      testing for 388, 396
squash 160                                                taxable operators 32
stable-sort 352, 399                                      testing
stacks                                                       incremental 37
   allocation on 150                                         of macros—see macros, testing
   of ATN registers 312                                   TEX vi, 5
   in continuations 260, 261                              tf 169
   use for iteration 264                                  Theodebert 236
   overﬂow of 396                                         three-valued logic 151
Steele, Guy Lewis Jr. ix, 43, 213, 395,                   till 154
         396                                              time 65, 359
Sterling, Leon 398                                        times of evaluation 224, 229
strings                                                   toggle 169
   building 57                                            top-down design 3
   matching 231, 244                                      trace 111, 266, 309
   as vectors 233                                         transition networks 306
Structure and Interpretation of Computer                  transformation
         Programs 18                                         embedded languages implemented by
structured programming 100                                          116, 241
subseq 244                                                   of macro arguments 107, 112
superclasses                                              trec 75
   precedence of 369                                      trees 70, 262
      sketch of 352                                          cross-products of 265
Sussman, Gerald Jay 18, 395                                  leaves of 72
symb 58                                                      recursers on 70
symbols                                                   true-choose
   building 57                                               breadth-ﬁrst version 304
   as data 385                                                   T implementation 396
   exported 383                                              depth-ﬁrst version 396
   imported 383                                           truncate 32
   interning—see intern                                   ttrav 74
   names of 57, 129, 382                                  Turing Machines vii
   see also: keywords                                     twenty questions 77
symbol-function 12, 388                                   typecase 62
symbolic computation 398                                  type-of 371
symbol-macrolet 105, 205, 210                             typep 243
symbol-name 58                                            types
symbol-package 381                                           declaration of 23
symbol-value 12, 178                                         specialization on 370
symbol-macros 105, 205, 236, 237                          typing 44, 112
swapping values 29
                                                          undefmethod 373
T 396                                                     uniﬁcation 394

---

union 206                                                 with-output-to-string 58
   unspeciﬁed order of result 207, 364                    with-places 237
unions 207                                                with-slots 236
unspecialized parameters 373                              with-struct 235
unwind-protect 148                                        writer’s cramp 44
:use 384                                                  &whole 95
user 381                                                  Woods, William A. 305
utilities 40                                              workstations 348
   as an investment 43, 392                               world, ideal 109
   become languages 113
   mistaken argument against 59                           X Windows vi, 5

var? 239                                                  zebra benchmark 396
variable capture—see capture
variables
   bound 16                                               #’ 10, 226
   free 16, 121                                           #( 233
   generalized—see generalized variables                  #. 75
   global 36, 125, 268, 379                               #: 128
varsym? 239                                               #? 226
   redeﬁned 335                                           #[ 227
vectors                                                   #\ 233
   for ATN registers 313                                  #{ 229
   creating with backquote 86                             ’ 225
   matching 231, 244                                         see also: quote
visual aspects of source code 30, 213,                    , 84
         231                                              ,@ 86, 138
voussoirs 8                                               : 383
values 32                                                 :: 382
   inversion for 393                                      @ 294
=values 267                                                240, 252, 328
                                                          ‘ see backquote
                                                          | 58
wait 280
Wand, Mitchell 395
Weicker, Jacqueline J. x
when-bind 145
when-bind* 145
while 154
with-answer 251
  redeﬁned 255
with-array 234
with-gensyms 145
with-inference 324
  redeﬁned 335, 340
with-matrix 234
with-open-file 147



---
```
