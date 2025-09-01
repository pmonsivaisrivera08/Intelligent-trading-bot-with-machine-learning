This project features an Intelligent Trading Bot designed to analyze financial markets and generate buy or sell trading signals. Unlike traditional trading systems based on fixed rules, this bot leverages Machine Learning and advanced feature engineering to identify complex patterns in historical price and volume data.

The bot operates in two main modes:

Offline Training: It analyzes one year of historical data to train a Machine Learning model (RandomForestClassifier). It uses a wide range of advanced technical indicators, such as RSI, MACD, and the Ichimoku Cloud, to create a robust feature set. The process includes cross-validation (StratifiedKFold) and hyperparameter tuning (GridSearchCV) to optimize the model's performance. After training, it performs a full backtest to simulate its historical performance, calculating key metrics like total return, Sharpe Ratio, and Maximum Drawdown, and visualizes the results on a graph.

Online Prediction: It uses the trained model to analyze real-time data for an asset and generate a trading signal (buy, sell, or hold). It provides a textual justification for buy signals based on the indicators that influenced the decision, offering transparency in the process.

The bot can work with cryptocurrencies (like BTC, ETH) and stocks (like AAPL), downloading data from reliable sources such as Yahoo Finance and Stooq. It's a powerful tool for anyone interested in algorithmic trading and the application of artificial intelligence in the markets.
___________________________________________________________________________________________________________________________________
Este proyecto presenta un Bot de Trading Inteligente, diseñado para analizar mercados financieros y generar señales de trading de compra o venta. A diferencia de los sistemas de trading tradicionales basados en reglas fijas, este bot utiliza Machine Learning y una ingeniería de características avanzada para identificar patrones complejos en los datos históricos de precios y volumen.

El bot opera en dos modos principales:

Entrenamiento Offline: Analiza un año de datos históricos para entrenar un modelo de Machine Learning (RandomForestClassifier). Utiliza una amplia gama de indicadores técnicos avanzados, como el RSI, MACD, y la Nube de Ichimoku, para crear un conjunto de características robusto. El proceso incluye la validación cruzada (StratifiedKFold) y el ajuste de hiperparámetros (GridSearchCV) para optimizar el rendimiento del modelo. Después del entrenamiento, realiza un backtesting completo para simular su desempeño histórico, calculando métricas clave como el retorno total, el Sharpe Ratio y el Maximum Drawdown, y visualiza los resultados en un gráfico.

Predicción Online: Utiliza el modelo entrenado para analizar datos en tiempo real de un activo y generar una señal de trading (compra, venta, o mantener). Proporciona una justificación textual para las señales de compra basada en los indicadores que influyeron en la decisión, ofreciendo transparencia en el proceso.

El bot puede operar con criptomonedas (como BTC, ETH) y acciones (como AAPL), descargando los datos de fuentes fiables como Yahoo Finance y Stooq. Es una herramienta poderosa para aquellos interesados en el trading algorítmico y la aplicación de la inteligencia artificial en los mercados.
