-PL-

Celem projektu było opracowanie systemu do klasyfikacji wykorzystującego głębokie i konwolucyjne sieci neuronowe i sprawdzenie, czy możliwe jest rozróżnienie dźwięków pojazdów z wyróżnieniem na 2 grupy:
nadjeżdżający pojazd do pasów bezpieczeństwa, czy skrzyżowania, a ciągły hałas ruchu ulicznego.

Aby to wykonać, autor opracował autorską bazę plików dźwiękowych, które zostały zarejestrowane, nagrywając dźwięki pojazdów na ulicach Krakowa. Próbki zostały znormalizowane, obrobione i po etykietowane w celu dalszego przetworzenia.

Zbiór danych został następnie przeanalizowany i przetworzony do formy spektrogramów, a docelowo mel-spektrogramów, aby skutecznie uczyć model sieci konwolucyjnych.

Proces klasyfikacji opierał swoje działanie na rozbudowanym modelu głębokich sieci neuronowych, którego podstawa składała się z warstw konwolucyjnych, wspomaganych o warstwy sieci głębokich czy elementy usprawniające działanie sieci takie jak dropout, czy max-pooling.

Trening sieci był długotrwałym etapem i żeby poprawić wstępne wyniki predykcji, wykonano ingerencje w  strukturę modelu czy optymalizacje hiperparametrów sieci. Ostatecznie udało się uzyskać wysoką skuteczność klasyfikacji w granicach 80%, 
a najlepszy model potrafi klasyfikować próbki z bazy nawet z 90% dokładnością. Aby sprawdzić działanie modelu w bardziej uogólnionym przypadku, przeprowadzono również proces k-krotnej walidacji krzyżowej i autor sprawdził tym samym
działanie modelu dla całego zbioru danych, a nie tylko jego wycinku. Tutaj ponownie uzyskano wysokie wyniki predykcji wynoszące ostatecznie powyżej 85%.

Na końcu dokonano również analizy uzyskanych danych, porównując rzeczywiste grupy plików audio z przewidywanymi, identyfikując błędnie sklasyfikowane próbki, których określenie może prowadzić do poprawy działania systemu w przyszłości.

Całość projektu można określi jako sukces, ponieważ oprócz skutecznego rozróżnienia 2 zdefiniowanych grup dźwięków, uzyskano wysoką wartość poprawnych klasyfikacji a model wraz z całym opracowanym systemem, w pełni poradził sobie z zaplanowanym zadaniem.
Dodatkowym atutem projektu jest wykonana u standaryzowana autorska baza próbek dźwięków pojazdów w miastach, która może być szerzej wykorzystywana i stanowi potencjalny człon oraz podstawę do badania innych rozwiązań.

-ENG-

The main goal of the project was to develop a classification system using deep neural networks and to test, whether it is possible to distinguish between vehicle sounds with a distinction between 2 groups: 
oncoming vehicle noise for safety lanes or intersections, and continuous traffic noise.

To do this, the author developed an original database of sound files that were recorded on the streets of Krakow (Poland). The samples were normalised, processed and labelled for further processing.

The dataset was then analysed and processed into the form of spectrograms, and ultimately mel-spectrograms, to effectively teach the convolutional network model.

The classification process was based on a deep neural network model, the basis of which consisted of convolutional layers, supported by deep network layers or additional supportive elements, such as dropout or max-pooling.

The training of the network was a lengthy stage and, in order to improve the initial prediction results, interventions were made in the model structure or optimisations of the network hyperparameters. In the end, a high classification efficiency of 80% was achieved, 
and the best model can classify samples from the database with up to 90% accuracy. In order to test the performance of the model in a more generalised case, a k-fold cross-validation process was also carried out and the author thus verified the
the performance of the model for the entire dataset. Here again, high prediction scores of ultimately above 85% were obtained.

Finally, an analysis of the resulting data was also carried out, comparing the actual groups of audio files with the predicted ones, identifying misclassified samples, the identification of which may lead to improved system performance in the future.

The whole project can be described as a success, because in addition to successfully distinguishing the 2 defined groups of sounds, a high value of correct classifications was obtained and the model, together with the entire developed system,
can well deal with the planned task. An additional success of the project is to carry out the standardised database of urban vehicle sound samples, which can be used more widely and provides a potential member and basis for testing other solutions.
