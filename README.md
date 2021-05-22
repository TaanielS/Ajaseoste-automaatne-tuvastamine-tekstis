# Ajaseoste-automaatne-tuvastamine-tekstis

Taaniel Saarniku bakalaureuse lõputöö praktilise osa failid.
Juhendaja: Siim Orasmaa

Sisaldab koodi EstTimeMLCorpus'es olevate andmete viimiseks EstNLTK 1.6 Text objektideks, sündmusi tuvastavate ja ajaseoseid tuvastavate mudelite loomiseks. Täpsemad Jupyter Notebook failide selgitused on nende failide alguses kirjas.
Lisaks on sündmuste ja ajaväljenditega seotud relatsioonide failid (relations.pickle, relations_only_main.pickle, relations_only_sub.pickle).
Kaustas "mapping" on .pickle failid, mis sisaldavad korpuse ja Text.words sõnestamisel saadud sõnede ühendamiseks loodud sõnestikku (lause_nr_korpuses, sona_nr_korpuses) -> (text.start, text.end). Lisameetodiga saab vastava(d) sõne(d) Text.words seest kätte.
Kaust "artiklid" sisaldab töödeltud artikleid .json failidena.
Kaust "artiklid_embeddingutega" on mõeldud töödeltud artiklide jaoks, mille sõnadele on lisatud erinevaid BERT-i peidetud kihi vektoreid. Võimalik ise need koostada või Drive'st alla tõmmata.
