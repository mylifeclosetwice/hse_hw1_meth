# Домашнее задание 1
Ссылка на тетрадку: 
## Основная часть
Были проанализированы следующие 3 BS-Seq образца, полученные на разных стадиях развития эмбриона мыши:
  * SRR5836473 - 8 Cell
  * SRR5836475 - ICM
  * SRR3824222 - Epiblast
В целях экономии времени и ресурсов, прочтения 3 образцов были выровнены на 11 хромосому мыши.
### FastQC
Мы проанализировали образец 8 Cell. Из отчета видно, что уровень содержания GC у нашего образца сильно отклоняется от нормы: наблюдаются два пика, один около 70%, второй - около 20%. Заметим также, что подержание GC у нашего образца практически в два раза ниже, чем у РНК. (Файл с отчетом см. в репозитории)
### Статистика
![image](https://github.com/mylifeclosetwice/hse_hw1_meth/assets/71773580/46a4c1c8-3ea2-4d2e-87e7-f9f90db01d8c)

### Уровни метиллирования для отдельных образцов

8 Cell | ICM | Epiblast
-------|-----|---------
![image](https://github.com/mylifeclosetwice/hse_hw1_meth/assets/71773580/d5c71edf-20cc-4497-9e6b-d3fd88743ba6) | ![image](https://github.com/mylifeclosetwice/hse_hw1_meth/assets/71773580/785ae306-8226-495b-b204-7679bf62a8a8) | ![image](https://github.com/mylifeclosetwice/hse_hw1_meth/assets/71773580/4a812db3-e73b-43f1-8c04-8a4b1f96af51)

### Коллинг метилирование цитозинов
Из отчета (см. в репозитории) видно, что наибольший уровень метеллирования показывает образец Epiblast, за ним следует 8 cell, наименьший показатель - у ICM.
8 Cell | ICM | Epiblast
-------|-----|---------
![image](https://github.com/mylifeclosetwice/hse_hw1_meth/assets/71773580/b262c59b-130b-4440-b496-5e60e1803490) | 
![image](https://github.com/mylifeclosetwice/hse_hw1_meth/assets/71773580/4dbca2a4-eff2-47a6-b8c3-8d782e5c9d61) |


### Уровeнь метиллирования
![image](https://github.com/mylifeclosetwice/hse_hw1_meth/assets/71773580/f87f8f5c-1602-4607-9ef9-38d6c0aa4ac2)

### Уровeнь покрытия
![image](https://github.com/mylifeclosetwice/hse_hw1_meth/assets/71773580/762de1c9-9911-4054-b19b-e55f507a8690)

