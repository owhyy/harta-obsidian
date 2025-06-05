# Macro

## Definiție

O **macro** este un mecanism prin care poți **scrie cod care generează cod**. Mai exact, o macro este o funcție specială care transformă o expresie înainte ca aceasta să fie evaluată de limbajul de programare.

Macro-urile permit extinderea limbajului și introducerea unor noi forme de sintaxă, adaptate domeniului de aplicare, fără a modifica compilatorul sau interpretorul.

## Limbaje care suportă macro-uri

- **[[LISP]] / [[Common Lisp]] / [[Scheme]] / [[Clojure]]** – suportă [[Macro|macro-uri]] foarte puternice, bazate pe transformarea expresiilor simbolice (*code as data*).
- **C / C++** – folosesc macro-uri simple cu `#define`, dar fără conștientizare de sintaxă.
- **Rust** – oferă un sistem de macro-uri sigur și expresiv (`macro_rules!` și procedural macros).
- **Elixir** – are macro-uri inspirate din LISP, datorită naturii sale metaprogramabile.

## Macro-uri în [[LISP]] (exemplu simplu)

```lisp
(defmacro unless (cond body)
  `(if (not ,cond) ,body))
