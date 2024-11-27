![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)


# Previsão de trajetória de carreira baseada em habilidades e experiência profissional

Este estudo investiga métodos eficientes para recomendar trajetórias de carreira com base na análise de currículos. Utilizando um conjunto de dados de pesquisas anteriores, que inclui históricos profissionais anotados com as respectivas URIs da ontologia ESCO, o objetivo é prever o próximo cargo na trajetória profissional de um indivíduo. A baseline utilizada como referência foi o "reversed history" para comparar com outras técnicas de recomendação, incluindo SKNN, S-SKNN, SF-SKNN, LSTM e abordagens híbridas que combinam habilidades profissionais e experiência de trabalho.

Utiliza como referência os dataset e métricas do trabalho [4](https://www.scopus.com/record/display.uri?eid=2-s2.0-85174860612&origin=inward&txGid=9a4d9536d191a3f9c6a2e394b4470e6e)

## Dataset
O dataset deste trabalho pode ser encontrado em:
https://huggingface.co/datasets/jensjorisdecorte/anonymous-working-histories



## References

1. Spyros Avlonitis, Dor Lavi, Masoud Mansoury, and David Graus. 2023. Career Path Recommendations for Long-term Income Maximization: A Reinforcement Learning Approach. *arXiv preprint arXiv:2309.05391* (2023).

2. Yehuda Baruch. 2004. Transforming careers: from linear to multidirectional career paths: organizational and individual perspectives. *Career Development International*, 9(1), 58–73.

3. European Commission. 2017. ESCO - European Skills, Competences, Qualifications and Occupations. Available at: [https://ec.europa.eu/esco/](https://ec.europa.eu/esco/). Accessed: 2024-11-27.

4. Jens-Joris Decorte, Jeroen Van Hautte, Johannes Deleu, Chris Develder, and Thomas Demeester. 2023. Career Path Prediction using Resume Representation Learning and Skill-based Matching. *CEUR Workshop Proceedings 3490* (2023). Available at: [https://www.scopus.com/inward/record.uri?eid=2-s2.0-85174860612&partnerID=40&md5=9d7a9444045bb26dcdad6e84ddde8fe7](https://www.scopus.com/inward/record.uri?eid=2-s2.0-85174860612&partnerID=40&md5=9d7a9444045bb26dcdad6e84ddde8fe7). 

6. Hamid Hassan, Mujahid Hussain, Amna Niazi, Yasuo Hoshino, Akbar Azam, and Ahmad Shabbar Kazmi. 2022. Career path decisions and sustainable options. *Sustainability*, 14(17), 10501.

7. Roan Schellingerhout, Volodymyr Medentsiy, and Maarten Marx. 2022. Explainable Career Path Predictions using Neural Models. In *HR@RecSys*.

8. World Economic Forum. 2023. The Future of Jobs Report 2023. *Technical Report*, World Economic Forum. Available at: [https://www3.weforum.org/docs/WEF_Future_of_Jobs_2023.pdf](https://www3.weforum.org/docs/WEF_Future_of_Jobs_2023.pdf). Accessed: 2024-10-23.