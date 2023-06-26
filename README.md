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
![image](https://github.com/mylifeclosetwice/hse_hw1_meth/assets/71773580/75441ec8-484a-4d6b-9299-1090d2606e69)

### Уровни метиллирования для отдельных образцов

8 Cell | ICM | Epiblast
-------|-----|---------
![image](https://github.com/mylifeclosetwice/hse_hw1_meth/assets/71773580/d5c71edf-20cc-4497-9e6b-d3fd88743ba6) | ![image](https://github.com/mylifeclosetwice/hse_hw1_meth/assets/71773580/785ae306-8226-495b-b204-7679bf62a8a8) | ![image](https://github.com/mylifeclosetwice/hse_hw1_meth/assets/71773580/4a812db3-e73b-43f1-8c04-8a4b1f96af51)

### Коллинг метилирование цитозинов
Из отчета (см. в репозитории) видно, что наибольший уровень метеллирования показывает образец Epiblast, за ним следует 8 cell, наименьший показатель - у ICM.
8 Cell | ICM | Epiblast
-------|-----|---------
![image](https://github.com/mylifeclosetwice/hse_hw1_meth/assets/71773580/b262c59b-130b-4440-b496-5e60e1803490) | ![image](https://github.com/mylifeclosetwice/hse_hw1_meth/assets/71773580/c69941ef-70a1-493c-9a15-b6c940e395d6) | ![image](https://github.com/mylifeclosetwice/hse_hw1_meth/assets/71773580/4e19de9b-317b-4729-87b4-e08583cd9628)


![image](https://github.com/mylifeclosetwice/hse_hw1_meth/assets/71773580/4dbca2a4-eff2-47a6-b8c3-8d782e5c9d61) | ![image](https://github.com/mylifeclosetwice/hse_hw1_meth/assets/71773580/d19ed923-aa31-4c75-a9a7-931e47e12112) | ![image](https://github.com/mylifeclosetwice/hse_hw1_meth/assets/71773580/c2e2f57e-cd22-4c03-90af-5f8898becbb1)

### Уровeнь метиллирования
![image](https://github.com/mylifeclosetwice/hse_hw1_meth/assets/71773580/ab59a18f-4ea6-4a23-b2f7-71ba03946e66)

### Уровeнь покрытия
![image](https://github.com/mylifeclosetwice/hse_hw1_meth/assets/71773580/2eac6dab-3b7c-41eb-bbdd-7e1f8898e770)


