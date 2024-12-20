# Weather App 🌦️

Este é um projeto simples de uma aplicação de clima que utiliza a API do OpenWeatherMap para buscar informações meteorológicas com base no nome de uma cidade. A aplicação exibe a temperatura, descrição do clima, um ícone representativo, umidade e velocidade do vento.

---

## Tecnologias Utilizadas 🛠️

- **HTML5**: Estrutura da aplicação.
- **CSS3**: Estilização e layout responsivo.
- **JavaScript**: Lógica da aplicação e consumo da API.
- **FontAwesome**: Ícones para melhorar a experiência visual.
- **API do OpenWeatherMap**: Para obter dados climáticos em tempo real.

---

## Funcionalidades ✨

- Busca de informações meteorológicas por cidade.
- Exibição de:
  - Temperatura atual (em °C).
  - Descrição do clima (ex.: ensolarado, chuvoso).
  - Umidade relativa do ar.
  - Velocidade do vento.
  - Ícone representativo do clima.
- Mensagem de erro personalizada para locais não encontrados.

---

## Estrutura do Projeto 📂

weather-app/
|— index.html
|— style.css
|— index.js
|— images/
    |— clear.png
    |— rain.png
    |— snow.png
    |— cloud.png
    |— mist.png
    |— 404.png


---

## Pré-requisitos ⚙️

1. **Chave da API do OpenWeatherMap**: Obtenha sua chave em [OpenWeatherMap](https://openweathermap.org/api) e substitua `Your Api Key` no arquivo `index.js` pela sua chave válida.

2. **Servidor Local**: Recomenda-se usar um servidor local como o Live Server para evitar problemas de CORS.

---

## Como Usar 🚀

1. Clone este repositório:
   ```bash
   git clone https://github.com/zearanha/weather-app.git

Exemplo de Uso 🖥️
Digite "New York" no campo de busca.
Clique no ícone de lupa.
Veja a temperatura, descrição do clima, umidade e velocidade do vento para a cidade de Nova York.


Melhorias Futuras 🔮
Adicionar suporte para localização automática com base no GPS do usuário.
Permitir troca de unidades (Celsius, Fahrenheit, Kelvin).
Adicionar previsão de clima para os próximos dias.

Licença 📜
Este projeto é open-source e está sob a Licença MIT.

Feito com ❤️ por José de Aranha Falcão Neto.
