# Aplikacija
Spring Boot web aplikaciju za jednostavni CRUD.
Servis mora biti otporan na Brute Force napad.

1. Username i Password moraju biti uskladisteni u bazi podataka PostgreSql.
2. Password mora biti enkriptovan.
3. Korisnik mora imati tri dozvoljena pokusaja.
4. Nakon treceg neuspesnog pokusaja, nalog se zakljucava.
5. Nakon uspesnog pokusaja, brojac neuspesnih pokusaja se resetuje.
6. Nakon 30 minuta, nalog se automatski otkljucava.


### Uvod

Da bismo implementirali Spring Boot aplikaciju koja je otporna na brute force napade, možemo koristiti Spring Security zajedno sa Postgres bazom podataka. Ova aplikacija će obuhvatiti sve navedene funkcionalnosti: čuvanje korisničkog imena i enkriptovanog passworda, praćenje broja neuspešnih pokušaja prijave, zaključavanje naloga nakon tri neuspešna pokušaja i automatsko otključavanje nakon 30 minuta.


### Zakljucak
Ova aplikacija koristi Spring Security i PostgreSQL za autentifikaciju i zaštitu od brute force napada. Lozinke su enkriptovane, nalog se zaključava nakon 3 neuspešna pokušaja prijave, a nakon 30 minuta se automatski otključava.

