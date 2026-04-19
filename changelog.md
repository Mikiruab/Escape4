## 15.04.2026 klecha/yurii: 
dodano generowanie nowego place na bazie "game" jako prywatne dla kazdego nowego party przy uzyciu createplaceasync, safeteleport, teleportservice. polegajace na tworzeniu kodu party i prywatnego klucza do ktorego dostęp ma tylko party. zabezpieczenia przed dołączeniem z poza gry, nie pokazuje sie na server liscie i nie da sie dolaczyc, tylko safeteleport i komendy administratora - mikiruab, jurathegamerRUS (;join [partycode])

## 16.04.2026 klecha: 
zmiana oświetlenia i atmosfery dla "game". dodanie latajacego pokoju w ktorym spawnowac bedzie sie gracz, jest to sala komputerowa 155b, nowy model biurka, i propozycja dla modelu kolejnego biurka (tego starego dla uczniow). + zmiana oswietlenia lobby (fog offset i inne ten teges)
++ faktycznie dodano komende ;join [partycode].
// dodać wiecej biurek, znalezc jakies stare krzesla (rozne kolory, niebieski i czerwony) obrotowe, komputerowe ale takie metalowo-drewniane. zrobić oświetlenie na bazie tego co jest faktycznie.

## 17.04.2026 yurii: 
zmieniłem ui dla stworzenia party, zmieniłem logo i thumbnail gry, w lobby dodałem nowe propy, oczyściłem niepotrzebne stringi w lokalizacjach, które nie są używane. w "game", zmieniłem i naprawiłem sprint ui, zanchorowałem niektóre obiekty, poprzemieszczałem i zmieniłem cursor (chciałem dodać, żeby można było odblokować kursor, ale nie da się, bo coś blokuje skrypt, więc usunąłem)

## 18.04.2026 yurii:
znowu pozmieniałem ui (kolory i żeby na telefonie było na pełny ekran a nie poza bezpieczny obszar), dodałem kastomowe animacje idle, walk, running etc... , postprocessing (vignette, film grain), male poprawki i chyba tyle.

## 19.04.2026 yurii:
zrobilem duzo rzeczy ale wkrotce powiem: naprawilem party ui ktory wczoraj zmienilem, dodalem kastomowy ui dla rzeczy w ekwipunku, dodalem system zbierania rzeczy (dodaje i usuwa dla wszystkich {wrzuca do serverstorage jakby byl softlock}, uzywa tagi i attributes dla nazwy, dzwieku, ikonki), system z drzwiami (uzywa tagi i attributes dla wyznaczenia drzwi i potrzebnego przedmiotu dla otwarcia. {w planach animacje otwierania bez i z przedmiotem ale to potem bo jestem zmeczony}), system proximity prompt i podswietlania, zmieniłem jak trzyma sie przedmiot (ale nie wiem moze jescze sie zmieni), zmniejszylem intensywnosc dof (zaczal strasznie denerwowac mnie) no i w sumie tyle, jestem wykonczony.
