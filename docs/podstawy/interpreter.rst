Interpreter Pythona
#######################

Siła Pythona tkwi m. in. w standardowej bibliotece udostępniającej wiele
funkcjonalności, a także w wielu rozszerzeniach zapewnianych przez instalację
dodatkowych modułów. W Pythonie łatwo stworzymy aplikacje konsolowe, wyposażone
w interfejs graficzny, sieciowe, bazodanowe, multimedialne itd.

W systemach opartych na Linuksie :term:`interpreter` Pythona jest standardowo zainstalowany,
ponieważ duża część oprogramowania na nim bazuje. W systemach Microsoft Windows Pythona
należy :ref:`doinstalować <ins-python>`. Interpreter tłumaczy (kompiluje w locie) kod i od razu go wykonuje.
Interpreter Pythona może być używany w trybie interaktywnym do nauki i testowania
kodu.

Prosty kod można testować w interpreterze, do tworzenia bardziej rozbudowanych
skryptów wykorzystać możemy dowolny edytor tekstowy. Ze względów praktycznych
warto korzystać z programów ułatwiających pisanie kodu (obsługa wcięć,
podświetlenia itd.) tzw. IDE czyli `Integrated Development Environment <http://pl.wikipedia.org/wiki/Zintegrowane_%C5%9Brodowisko_programistyczne>`_
np. lekkie i szybkie :ref:`Geany <geany-python>` lub profesjonalne środowisko
:ref:`PyCharm <pycharm-python>`. Obydwa programy działają na platformie Linux i Windows.

Zanim przystąpimy do pracy w katalogu domowym utworzymy podkatalog ``python``,
w którym będziemy zapisywali nasze skrypty:

.. raw:: html

    <div class="code_no">Kod nr <script>var code_no = code_no || 1; document.write(code_no++);</script></div>

.. code:: bash

    ~$ mkdir python
    ~$ cd python

Interpreter Pythona uruchamiamy poleceniem:

.. code:: bash

    ~$ python

Po uruchomieniu interpreter wyświetli swoją wersję, wersję kompilatora C++ (``GCC``),
informację o sposobie uzyskania pomocy (polecenie ``help``), na końcu zaś
znak zachęty ``>>>``.

.. note::

    Można równierz korzystać z rozszerzonej konsoli Pythona uruchamianej poleceniem
    ``ipython``. Oferuje ona kolorowane wyjście, ułatwia wszelkiego rodzaju interaktywne obliczenia.

    Przykłady zawierające znak zachęty ``$`` oznaczają komendy
    do wykonania w terminalu systemu operacyjnego (w Xubuntu uruchom przez :kbd:`Win+T`).

    Komendy kopiujemy i wklejamy do terminala bez znaku zachęty ``$`` i poprzedzającego tekstu
    za pomocą środkowego klawisza myszki lub skrótu :kbd:`CTRL+SHIFT+V`.