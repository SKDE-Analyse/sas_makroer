[Ta meg tilbake.](./)


# Unik_pasient

Unik_pasient Makro - Opprettet 1/12-15 av Frank Olsen
For � finne unike pasienter, oppholdsnr og antall opphold pr pasient ut fra et "merke"
Unik_pasient(inn_data=, pr_aar=, sorter=, Pid=, Merke_variabel=)
Parametre:
1. Inn_data: datasett man utf�rer analysen p�
2. pr_aar: settes=aar dersom man �nsker � finne unike pasienter pr �r, ellers la st� tom
3. sorter: Andre variable det skal sorteres p�, f.eks inndato og utdato
4. Pid: Settes=PID s� lenge PID angir pasientid
5. Merke_variabel: Variabel det skal telles opp fra, m� v�re merket med 1 for aktuelle

Det lages tre nye variable i datasettet:
1. Unik_Pas_"Merke_variabel" --> lik 1 for unike pasienter
2. Nr_pr_pas_"Merke_variabel" --> Nummererer de aktuelle oppholdene pr pasient i rekkef�lge
3. N_pr_pas_"Merke_variabel" --> Antall opphold totalt pr pasient, settes p� alle opphold