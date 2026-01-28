# Iqoption-
Señales Inteligente 🧠 
eur usd otc 1 miunto 
eur jpy otc 1miunto 
mandame las señales ami bot de Telegram 
conectar mi bot de Telegram  
IQ_USER = "tu_ 
IQ_PASS = "tu_
TELEGRAM_TOKEN "TU_TELEGRAM_BOT_TOKEN"@Henbot4_bot
CHAT_ID = "ID_DE_TU_CHAT_O_CANAL" # Ej: -1008313904219

# Inicializar Bot de Telegram
bot =@Henbot4_bot TeleBot(TELEGRAM_TOKEN)8313904219:AAGrk7sDzZewAd43MJMoGHbDRB06qGzDoDs

# Conectar a IQ Option
iq_api = IQ_Option(IQ_USER, IQ_PASS)
status, reason = iq_api.connect()

if status:
    print("✅ Conexión exitosa a IQ Option")
        bot.send_message(CHAT_ID, "🤖 Bot de Señales 

        def get_signal(asset):
            """
                Lógica de ejemplo: Usa el indicador RSI para generar señales.
                    """
                        # Pedir velas de 1 minuto
                            candles = iq_api.get_candles(asset, 60, 15, time.time())
                                
                                    # Aquí podrías calcular indicadores reales (RSI, MACD, etc.)
                                        # Por simplicidad, simularemos una lectura de precio:
                                            ultimo_precio = candles[-1]['close']
                                                
                                                    # Ejemplo de lógica: Si el precio termina en .00 es una 'señal' (Solo para test)
                                                        if str(ultimo_precio).endswith('0'):
                                                                return "COMPRA 🟢"
                                                                    elif str(ultimo_precio).endswith('5'):
                                                                            return "VENTA 🔴"
                                                                                return None

                                                                                # --- BUCLE PRINCIPAL ---
                                                                                ACTIVO = "EURUSD"

                                                                                try:
                                                                                    prin(f"Buscando señales para {ACTIVO}...")
                                                                                        while True:
                                                                                                senal = signal(ACTIVO)
                                                                                                        
                                                                                                                if senal:
                                                                                                                            mensaje = hola señales  de iqoption 
                                                                                                                             **NUEVA SEÑAL*
