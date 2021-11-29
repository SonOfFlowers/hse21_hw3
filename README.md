# hse21_hw3
## Первая часть
Ссылка на коллаб: https://colab.research.google.com/drive/1gUrSMXmm7oeMGmVgFgrasNmWQj2cR3zq?usp=sharing

## Сравнительная статистика из multiQC

![image](https://user-images.githubusercontent.com/93160309/143787987-8a9647b9-877e-4cc8-8f99-3699dde6f4e5.png)

![image](https://user-images.githubusercontent.com/93160309/143788075-115bb803-7a80-4354-8ea7-db512e852dd8.png)

![image](https://user-images.githubusercontent.com/93160309/143788102-04f40216-8a0e-4fb8-8752-3ba6dc6a3915.png)

![image](https://user-images.githubusercontent.com/93160309/143791586-2ed4231c-2293-41d5-9e30-857419673124.png)

![image](https://user-images.githubusercontent.com/93160309/143791642-3b734139-5056-409a-b232-1f1d2b83ee45.png)

![image](https://user-images.githubusercontent.com/93160309/143791664-f7df31fa-e72c-48aa-825f-5c8e5a613358.png)

![image](https://user-images.githubusercontent.com/93160309/143791691-13bdb689-8617-40e4-b6cd-4bbbffe64217.png)

## Суммарная статистика

![image](https://user-images.githubusercontent.com/93160309/143791745-6e55155d-73d2-4776-9655-1e4eba6ab199.png)

## Количество уникально картированных чтений по всем образцам в отдельности 

![image](https://user-images.githubusercontent.com/93160309/143791933-e45d7842-5014-4e18-978c-6e595391d2e7.png)

## По итогам подсчитывания количества чтений программой HTSeq находим количество чтений, которые могут принадлежать разным генам и количество чтений, соответствующее участкам генома, где не аннотировано ни одного экзона

![image](https://user-images.githubusercontent.com/93160309/143792158-49ff99b1-9544-407d-9e9a-9b815636c3d5.png)

![image](https://user-images.githubusercontent.com/93160309/143792169-a851d8d6-d399-474e-a4f6-3a73600b8fa7.png)

## Считаем количество чтений, которые соответствуют хотя бы одному гену, при помощи данных выше

![image](https://user-images.githubusercontent.com/93160309/143792273-0c3474c1-8be2-4f25-9c10-541e9e772143.png)

## Статистика по каждому образцу в отдельности 

Образец | Тип | Количество чтений | Успешно откартированные | Уникально откартированные | Кол-во чтений на ген
-|-|-|-|-|-
SRR3414629 | перепрограмированный | 21106089 |	20510113 (97.18%)	|	18375888 (87.06%)  | 16049609
SRR3414630 | перепрограмированный |	15244711 | 14832680 (97.30%)	|	13186139 (86.50%) |	11465324
SRR3414631 | перепрограмированный | 24244069 | 23547686 (97.13%) | 20928945 (86.33%) |	18408851
SRR3414635 | контроль | 20956475 |	20395865 (97.32%)	| 18428317 (87.94%) |	16275997
SRR3414636 | контроль | 20307147 |	19757059 (97.29%)	| 17825380 (87.78%) |	15757580
SRR3414637 | контроль | 20385570 |	19847291 (97.36%)	| 17844858 (87.54%) |	15736978

## Объединяем файлы с прочтениями в один (all_counts). c1, c2, c3 - контрольные образцы; r1, r2, r3 - перепрограммированные образцы

![image](https://user-images.githubusercontent.com/93160309/143936949-1eea5bcc-f949-4ca8-bd20-f045f7a6bc38.png)

## Вторая часть
Ссылка на коллаб: https://colab.research.google.com/drive/1Otq7ok20gkECfx8ciF9qRnDcdvqK2uJY?usp=sharing

## Смотрим Log2FC для генов с помощью MA-plot

![image](https://user-images.githubusercontent.com/93160309/143938438-6d6ec846-6c00-4493-9459-2fbf6114592b.png)
### Большее количество дифференциально экспрессированных генов увеличило свою экспрессию


## Heatmap, показывающий созависимость экспрессии генов из контрольных и репрограммированных образцов

![image](https://user-images.githubusercontent.com/93160309/143952471-5d07f184-2f01-4427-8f5e-141d132a8850.png)
### Экспрессия генов одинакова в одной группе образцов и отличается между группами


## Heatmap для первых 20 наиболее дифференциально экспрессированных генов

![image](https://user-images.githubusercontent.com/93160309/143953321-5b051430-d073-4b57-9b5c-7fcdb5edd159.png)

## Графики со значениями "Normalized counts" в контрольных и перепрограммированных образцах

![image](https://user-images.githubusercontent.com/93160309/143954284-8f8500c4-bb59-4de6-8371-cb977f14039c.png)

![image](https://user-images.githubusercontent.com/93160309/143954313-0bbeb63e-6fee-49ab-99ec-ea5044544c85.png)

![image](https://user-images.githubusercontent.com/93160309/143954347-e675cca7-443f-4890-99c1-806ead432e0c.png)

![image](https://user-images.githubusercontent.com/93160309/143954437-b8163073-7ceb-4c9c-b65e-8da678be843c.png)




