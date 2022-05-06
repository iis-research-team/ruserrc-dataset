# Scientific paper aspects dataset

This part contains 591 abstracts of Russian scientific papers annotated with aspects:
- 79 texts in `aspects_data_part_1.csv`;
- 212 texts in `aspects_data_part_2.csv`;
- 300 texts in `aspects_data_part_3.csv` (this part of the dataset was automatically labelled and manually edited).

The dataset contains 4304 aspects:

| Aspect                | Number|
|-----------------------|-------|
| Task                  |    488|       
| Goal                  |    125|
| Contribution (Contrib)|   1725|
| Method                |    626|
| Tool                  |    391|
| Use                   |    378|
| Advantage (Adv)       |    338|
| Example               |     63|
| Conclusion (Conc)     |    170|


An example of annotated text:

`<Contrib> Рассматриваются подходы к решению задачи <Task> поиска параметров SVM-классификатора </Task> на основе <Method> гибридизации алгоритма роя частиц (PSO-алгоритм) </Method> и <Method> алгоритмов поиска по сетке </Method> </Contrib> с целью <Goal> обеспечения высокого качества классификационных решений </Goal>. В работе <Contrib> представлены две гибридные версии базового PSO-алгоритма </Contrib>, предполагающие использование соответственно <Method> классического алгоритма Grid Search (GS-алгоритм) </Method> и <Method> алгоритма Design of Experiment (DOE-алгоритм) </Method>. При этом в качестве базового используется <Method> канонический PSO-алгоритм </Method>. Результаты проведенных исследований <Conc> демонстрируют целесообразность применения <Method> гибридных версий базового PSO-алгоритма </Method> </Conc> с целью <Adv> сокращения временных затрат на поиск оптимальных значений параметров SVM-классификатора при сохранении высокого качества его классификационных решений </Adv>. <Contrib> Рассмотрены прямые методы <Task> решения систем линейных алгебраических уравнений (СЛАУ) </Task> </Contrib> в системах компьютерной математики <Tool> MathCAD Prime </Tool> и <Tool> MathCAD 14 </Tool>. Приведены примеры использования встроенных функций c оценкой их погрешности на примере <Example> глобальной интерполяции каноническим полиномом </Example>.`
