ФИО: Еремеев Александр Николаевич
Группа: Б9123-09.03.01 цд

## Юнит-тесты (32 теста)

PokemonListViewModelTest — 11 тестов: загрузка списка, ошибка, retry, пустой результат, поиск, добавление и удаление избранных, дубликаты, отражение избранных в состоянии, обновление списка.

PokemonDetailViewModelTest — 5 тестов: начальное состояние, успешная загрузка, ошибка, retry, корректная передача pokemonId через SavedStateHandle.

PokemonRepositoryTest — 6 тестов: получение списка, ошибка сети, кэширование деталей, поиск с пустой строкой, поиск без учёта регистра, возврат кэша при недоступности сети.

FavouriteRepositoryUnitTest — 5 тестов: получение Flow из DAO, добавление, удаление, isFavourite true/false.


## Интеграционные тесты (15 тестов)

FavouriteDaoTest — 7 тестов: добавление и чтение через Flow, удаление, дубликаты, isFavourite, последовательность эмиссий Flow.

FavouriteRepositoryIntegrationTest — 4 теста: добавление через репозиторий и чтение из Flow, изменения Flow при add/remove, дубликаты, isFavourite.

PokemonListViewModelIntegrationTest — 4 теста: сохранение избранного в Room, удаление из Room, дубликаты, переход из Error в Success после retry.
