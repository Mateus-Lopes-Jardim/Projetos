# Projetos
Esta é a "Calculado de consumo de energia". Feita para medição de consumo diário ou eventual de equipamentos elétricos. Codado em Python, usando a fórmula consumoMensal = (potencia * horasDia * 30) / 1000. Após dar "Run" no programa, fazer os inputs de dados e ele calculará segundo informações prestadas.

# Solicita os dados do usuário
aparelho = input("Digite o nome do aparelho: ")
potencia = float(input("Digite a potência do aparelho (em watts): "))
horas_dia = float(input("Digite o tempo médio de uso diário (em horas): "))

# Calcula o consumo mensal
consumo_mensal = (potencia * horas_dia * 30) / 1000

# Exibe o resultado
print(f"\nAparelho: {aparelho}")
print(f"Consumo mensal: {consumo_mensal:.2f} kWh")

![Static Badge](https://img.shields.io/badge/python-blue)
![Static Badge](https://img.shields.io/badge/energy-black)

git remote add origin https://github.com/mateu/projetos.git
git branch -M main
git push -u origin main
