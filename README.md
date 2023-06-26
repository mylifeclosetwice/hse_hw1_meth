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
![image](https://github.com/mylifeclosetwice/hse_hw1_meth/assets/71773580/ae60e9eb-d05e-4fa4-a293-48ebacf0abbf) | ![image](https://github.com/mylifeclosetwice/hse_hw1_meth/assets/71773580/785ae306-8226-495b-b204-7679bf62a8a8) | ![image](https://github.com/mylifeclosetwice/hse_hw1_meth/assets/71773580/4a812db3-e73b-43f1-8c04-8a4b1f96af51)



