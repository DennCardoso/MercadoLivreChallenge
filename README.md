# 📊 Internet Growth Analytics: Argentina  
*Análise da evolução do acesso à internet na Argentina (usuários, banda larga e fatores econômicos)*  

---

## 📌 Visão Geral  
Este projeto analisa o crescimento da internet na Argentina, incluindo:  
✅ Número de usuários de internet (% da população)  
✅ Assinaturas de banda larga fixa e móvel  
✅ Correlação com indicadores econômicos (PIB, investimentos em TIC)  
✅ Comparação regional (América Latina)  

**Objetivo**: Identificar tendências, disparidades regionais e possíveis causas do crescimento.  

---

## 🛠️ Ferramentas Utilizadas  
- **Visualização de Dados**: [Tableau Public](https://public.tableau.com/)  
- **Fontes de Dados**: Banco Mundial, INDEC, UIT (links abaixo)  
- **Pré-processamento**: Excel ou Python (opcional para limpeza de dados)  

---

## 📂 Estrutura do Projeto  
argentina-internet-growth
│── /data # Dados brutos e processados
│ │── raw/ # Arquivos originais (CSV, Excel)
│ └── processed/ # Dados tratados (prontos para análise)
│── /docs # Relatórios complementares
│── /images # Prints das visualizações
│── argentina_dashboard.twb # Arquivo do Tableau
└── README.md # Este arquivo


---

## 🔗 Fontes de Dados  
1. **Banco Mundial**  
   - [Usuários de Internet (% população)](https://data.worldbank.org/indicator/IT.NET.USER.ZS)  
   - [Assinaturas de Banda Larga](https://data.worldbank.org/indicator/IT.NET.BBND)  
2. **INDEC** (Instituto Nacional de Estatística da Argentina)  
   - [Censos e pesquisas de TIC](https://www.indec.gob.ar/)  
3. **UIT** (União Internacional de Telecomunicações)  
   - [Indicadores globais de TIC](https://www.itu.int/en/ITU-D/Statistics/Pages/stat/default.aspx)  

---

## 📊 Principais Visualizações  
1. **Evolução Temporal**  
   - Gráfico de linha: Crescimento de usuários de internet (2000-2023)  
   - Comparação com países vizinhos (Chile, Uruguai, Brasil)  

2. **Banda Larga Fixa vs. Móvel**  
   - Gráfico de barras empilhadas: Penetração por tipo de conexão  

3. **Fatores Econômicos**  
   - Dispersão: Relação entre PIB per capita e acesso à internet  

4. **Mapa de Cobertura**  
   - (Se dados disponíveis) Distribuição geográfica por província  

---

## 🚀 Como Executar o Projeto  
1. **Baixe os dados** das fontes listadas acima (salve em `/data/raw`).  
2. **Processe os dados** (se necessário) usando:  
   - Excel (filtros, fórmulas)  
   - Python (Pandas para limpeza)  
3. **Importe para o Tableau** e abra o arquivo `argentina_dashboard.twb`.  
4. **Atualize as conexões** para apontar para seus dados locais.  

---

## 📌 Conclusões  
- A Argentina teve um **crescimento acelerado** de usuários de internet após 2010, impulsionado pela banda larga móvel.  
- **Desigualdades regionais**: Grandes cidades (Buenos Aires, Córdoba) têm cobertura superior a zonas rurais.  
- **Recomendações**: Expandir infraestrutura em províncias menos atendidas e promover planos acessíveis.  

---

## 💡 Melhorias Futuras  
- Adicionar dados de **velocidade média de internet** (Ookla, Speedtest).  
- Incluir **redes sociais** como indicador de uso (Facebook, Instagram).  
- Comparar com **políticas públicas** (ex.: "Argentina Conectada").  

---

## 📄 Licença  
Este projeto é open-source sob licença [MIT](https://choosealicense.com/licenses/mit/).  

---

✉️ **Contato**  
Se tiver dúvidas ou sugestões, abra uma *issue* ou me chame no [LinkedIn](https://www.linkedin.com/seu-perfil).  

**Feito com ❤️ por [Seu Nome]**  