# Tematy do poruszania 
## 20-30 slajdów

---

# Tranzystor bipolarny

* budowa - składa się z 3 warstw półprzewodnika o różnym typie przewodnictwa w dwóch możliwych ułożeniach pnp i npn poszczególne warstwy noszą nazwy
[pnp]("pnp.png"),[npn]("npn.png") w stanie aktywnym 

	1. emiter (E) warstwa silnie domieszkowana - co to znaczy?
	2. baza (B) warstw słabo domieszkowana i cieńsza
	3. kolektor (C)

	tworza sie przez to polaczenia p-n (połączenia połprzewodnikow o roznych typach przewodnictwa) 

* zasada działania - tranzystory w najprostszym ujęciu sterują prądem lub go wzmacniają, jeżeli do bazy przyłożymy niewielkie względem emitera napięcie to elektrony z emitera zaczną się przemieszczać w stronę bazy ale jako że warstwa bazy jest słabo domieszkowana i cienką to to duża część elektronów przemieści się do kolektora jako że mechanizm ten nie jest idealny to przez bazę płynie także nie wielki niepożądany prąd używamy natomiast prąd kolektora przez który przepływa zdecydowana większość elektronów. Stosunek prądu emitera do prądu bazy nazywamy wzmocnieniem prądowym i oznaczamy grecka β

# Wzmacniacze tranzystorowe (podstawy budowy) w układzie
wzmacniacz tranzystorowy to wzmacniacz w którym jako elementy czynne wykorzystywane są tranzystory dzielimy je z względu na to który element jest wspólny pomiędzy sygnałem wejściowym a wyjściowym 
* wspólnego emiter ![c_emiter](c_emiter.png) - najczęściej używany rodzaj wzmacniacza używa on do działania ułożenia dwóch rezystorów tworzących dzielnik napięcia  wzmacniane napięcie podawane jest pomiędzy bazę a emiter tranzystora, jako ze sygnał wyjściowy zbierany jest z emitera polaryzacja na wyjściu takiego układu jest odwrócona najczęściej wykorzystywany w wzmacniaczach niezbyt wysokich częstotliwości, oferują wysokie wzmocnienie napięciowe i prądowe.
* Wspólnicy kolektor ![c_kolektor](c_kolektor.gif) - produkuje napięcie wyjściowe na obciążeniu emitera które jest w fazie z napięciem Wejściowym ,nie podnosi napięcia, 
używany kiedy kiedy wejście o wysokiej impedancji musi być podpięte do wyjścia o niskiej wymagając wysokiego wzrostu natężenia nazwa bierze się z faktu ze kolektor tranzystora jest efektywnie uziemiony przez zasilacz. Napięcie wyjściowe odbierane jest pomiędzy kolektorem a emiterem wiec emiter jest wspólny dal wejścia i wyjścia nie wzmacnia napięcia charakteryzuje się dużym wzmocnieniem prądowym
* różnica w pracy pomiędzy nimi - są pewnego rodzaju przeciwieństwami siebie nawzajem pod względem budowy - 

# Pasmo przenoszenia wzmacniacza 

* definicja - Pasmo przenoszenia określa zakres częstotliwości, które są przenoszone przez dane urządzenie bez stratne  Wyobraźmy sobie sygnał od 1 Hz do 100 kHz, w którym wszystkie częstotliwości mają ten sam poziom. Po przejściu przez element audio okazuje się, że taki sygnał nie zostanie przeniesiony w całości. Wzmacniacze przenoszą bez strat sygnał analogowy w określonym przedziale częstotliwości, to jest w ich pasmie przenoszenia.W sprzęcie audio np granice tego pasma określone są jako częstotliwość której poziom jest 3 dB niższy od średniego norma dla takich urządzeń mówi ze powinny mieć pasmo przenoszenia od 20Hz do 20kHz lub szersze co ma zapewnić odpowiednie odtwarzanie w zakresie słyszalnym dla człowieka.

* sposób pomiaru
* znaczenie
* oporność wejściowa i wyjściowa wzmacniacza 
	
	1. definicja,
	2. sposób pomiaru
	3. znaczenie

# Wzmacniacze operacyjne

* układ odwracający
* układ nieodwracający.
* Porównanie parametrów (oporność wejściowa, wzmocnienie) i zastosowań

---

# źródła

* [tranzystor](https://ea.elportal.pl/bipolarne.html)
* [tranzystor wiki](https://pl.wikipedia.org/wiki/Tranzystor_bipolarny)
* [comon collector amplifier](https://www.electronics-tutorials.ws/amplifier/common-collector-amplifier.html)
* [common emiter amplifier](https://www.electronics-tutorials.ws/amplifier/amp_2.html)
 [złącze p-n](https://pl.wikipedia.org/wiki/Z%C5%82%C4%85cze_p-n)
 [transistor amplifier](https://www.tutorialspoint.com/amplifiers/transistor_as_an_amplifier.htm)
