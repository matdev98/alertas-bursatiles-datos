# Alertas bursátiles

**Ejecución UTC:** `2026-10-27T15:18:09Z`  
**Fecha de referencia:** `2026-10-27`  
**Proveedor:** Yahoo Finance via yfinance  
**Zona horaria:** America/New_York

Este archivo es texto estático. Los valores completos están en el JSON incluido al final.

## Resumen por activo
### MSFT
- Decisión: **ESPERAR / DATOS INSUFICIENTES**
- Última sesión cerrada: `2026-10-26`
- Cierre: `532.59998`
- Confluencia compra: `50.0`
- Confluencia venta: `12.5`
- Bloqueo de compra: `COMPRA BLOQUEADA: FECHA DE BALANCE NO VERIFICADA`

#### Indicadores
- **squeeze**: `NEUTRO` — applicable=True; momentum=7.61981; squeeze_on=True; squeeze_off=False; hist_color=green; release_now=False
- **rsi**: `COMPRA` — applicable=True; rsi14=57.23897; prev=52.61062
- **macd**: `NEUTRO` — applicable=True; macd=6.95797; signal=8.95323; histogram=-1.99525; prev_histogram=-2.30018
- **adx**: `COMPRA` — applicable=True; adx14=27.44372; plus_di=22.85327; minus_di=19.54744
- **volume_profile**: `COMPRA` — applicable=True; poc=398.8460568745931; vah=458.5896021525065; val=366.0291798909505; coverage_sessions=200; counted_volume=13507531826.0; note=Estimación de volumen por rango de velas; NO VP tick-by-tick ni el indicador original.
- **fair_value**: `VENTA` — applicable=True; fair_value=144.5077; margin_to_fv=-2.68562; method=DCF FCFF TTM; crecimiento limitado y supuestos declarados; margin_of_safety=0.2; buy_price_with_margin=115.60616; assumptions={'discount_rate': 0.1, 'terminal_growth': 0.03, 'fcf_growth': 0.05, 'forecast_years': 5}; source_fields=['free_cash_flow', 'shares_outstanding', 'net_debt']; current_price=532.59998; upside_to_intrinsic=-0.72867
- **koncorde**: `NEUTRO` — applicable=True; blue=8.35926; green=57.17744; brown=57.26431; red=80.9148
- **tendencia**: `COMPRA` — applicable=True; ema50=506.09285; ema200=461.76834

#### Fuentes, validación y advertencias
- Metadatos: `{"adjusted_prices": false, "currency": "USD", "daily_provenance": {"interval": "1d", "note": "Datos sujetos a disponibilidad, retrasos y límites de Yahoo Finance.", "requested_end": null, "requested_start": null, "retrieved_at_utc": "2026-10-27T15:18:11.197312+00:00", "source": "Yahoo Finance via yfinance", "source_url": "https://finance.yahoo.com/quote/MSFT", "ticker": "MSFT"}, "exchange": "NMS", "last_closed_candle": "2026-10-26", "metadata_provenance": {"interval": "metadata", "note": "Datos sujetos a disponibilidad, retrasos y límites de Yahoo Finance.", "requested_end": null, "requested_start": null, "retrieved_at_utc": "2026-10-27T15:18:11.919233+00:00", "source": "Yahoo Finance via yfinance", "source_url": "https://finance.yahoo.com/quote/MSFT", "ticker": "MSFT"}, "provider": "Yahoo Finance via yfinance", "ticker": "MSFT", "timezone": "America/New_York"}`
- Calidad: `{"closed_daily_only": true, "daily_hash": "b5039031ed12d99d23b2a2f9b646ba8cc369fe19ed0f7f9cbcacc254f048175f", "daily_rows": 500, "intraday_rows": 5072}`
- Earnings: `{"note": "N/D: Yahoo no expuso earnings_dates para este ticker.", "provider": {"interval": "earnings", "note": "Datos sujetos a disponibilidad, retrasos y límites de Yahoo Finance.", "requested_end": null, "requested_start": null, "retrieved_at_utc": "2026-10-27T15:18:14.259144+00:00", "source": "Yahoo Finance via yfinance", "source_url": "https://finance.yahoo.com/quote/MSFT", "ticker": "MSFT"}, "status": "N/D"}`
- Fair Value: `{"method": "DCF FCFF TTM (suma de cuatro trimestres)", "provider": {"interval": "financials", "note": "Datos sujetos a disponibilidad, retrasos y límites de Yahoo Finance.", "requested_end": null, "requested_start": null, "retrieved_at_utc": "2026-10-27T15:18:15.928451+00:00", "source": "Yahoo Finance via yfinance", "source_url": "https://finance.yahoo.com/quote/MSFT", "ticker": "MSFT"}, "status": "OK"}`
- Advertencias: `["Squeeze original LazyBear es la referencia por defecto; corrected=True usa multiplicador BB corregido.", "Koncorde reproduce la variante Pine de manboto; no se afirma equivalencia con la versión protegida de Marcos Emmi.", "Volume Profile reparte el volumen completo de cada vela en todos los niveles intersectados; no es volumen tick-by-tick.", "El porcentaje de confluencia es concordancia de criterios, no probabilidad estadística."]`

## Payload completo

```json
{
  "engine_version": "3.0.0",
  "execution_utc": "2026-10-27T15:18:09Z",
  "provider": "Yahoo Finance via yfinance",
  "publication": {
    "gist": {
      "gist_id": "32e489a9f846751ab511ed408a640ab3",
      "owner": "matdev98",
      "public_verified": true,
      "stable_json_url": "https://gist.githubusercontent.com/matdev98/32e489a9f846751ab511ed408a640ab3/raw/alertas_latest.json",
      "status": "OK"
    },
    "repository": {
      "status": "PENDING"
    }
  },
  "reference_session_date": "2026-10-27",
  "results": [
    {
      "asset_type": "equity",
      "buy_confluence_pct": 50.0,
      "buy_veto": "COMPRA BLOQUEADA: FECHA DE BALANCE NO VERIFICADA",
      "close_usd": 532.59998,
      "data_metadata": {
        "adjusted_prices": false,
        "currency": "USD",
        "daily_provenance": {
          "interval": "1d",
          "note": "Datos sujetos a disponibilidad, retrasos y límites de Yahoo Finance.",
          "requested_end": null,
          "requested_start": null,
          "retrieved_at_utc": "2026-10-27T15:18:11.197312+00:00",
          "source": "Yahoo Finance via yfinance",
          "source_url": "https://finance.yahoo.com/quote/MSFT",
          "ticker": "MSFT"
        },
        "exchange": "NMS",
        "last_closed_candle": "2026-10-26",
        "metadata_provenance": {
          "interval": "metadata",
          "note": "Datos sujetos a disponibilidad, retrasos y límites de Yahoo Finance.",
          "requested_end": null,
          "requested_start": null,
          "retrieved_at_utc": "2026-10-27T15:18:11.919233+00:00",
          "source": "Yahoo Finance via yfinance",
          "source_url": "https://finance.yahoo.com/quote/MSFT",
          "ticker": "MSFT"
        },
        "provider": "Yahoo Finance via yfinance",
        "ticker": "MSFT",
        "timezone": "America/New_York"
      },
      "data_quality": {
        "closed_daily_only": true,
        "daily_hash": "b5039031ed12d99d23b2a2f9b646ba8cc369fe19ed0f7f9cbcacc254f048175f",
        "daily_rows": 500,
        "intraday_rows": 5072
      },
      "decision": "ESPERAR / DATOS INSUFICIENTES",
      "earnings": {
        "note": "N/D: Yahoo no expuso earnings_dates para este ticker.",
        "provider": {
          "interval": "earnings",
          "note": "Datos sujetos a disponibilidad, retrasos y límites de Yahoo Finance.",
          "requested_end": null,
          "requested_start": null,
          "retrieved_at_utc": "2026-10-27T15:18:14.259144+00:00",
          "source": "Yahoo Finance via yfinance",
          "source_url": "https://finance.yahoo.com/quote/MSFT",
          "ticker": "MSFT"
        },
        "status": "N/D"
      },
      "engine_version": "3.0.0",
      "execution_utc": "2026-10-27T15:18:09Z",
      "fair_value_source": {
        "method": "DCF FCFF TTM (suma de cuatro trimestres)",
        "provider": {
          "interval": "financials",
          "note": "Datos sujetos a disponibilidad, retrasos y límites de Yahoo Finance.",
          "requested_end": null,
          "requested_start": null,
          "retrieved_at_utc": "2026-10-27T15:18:15.928451+00:00",
          "source": "Yahoo Finance via yfinance",
          "source_url": "https://finance.yahoo.com/quote/MSFT",
          "ticker": "MSFT"
        },
        "status": "OK"
      },
      "indicators": {
        "adx": {
          "adx14": 27.44372,
          "applicable": true,
          "minus_di": 19.54744,
          "plus_di": 22.85327,
          "state": "COMPRA"
        },
        "fair_value": {
          "applicable": true,
          "assumptions": {
            "discount_rate": 0.1,
            "fcf_growth": 0.05,
            "forecast_years": 5,
            "terminal_growth": 0.03
          },
          "buy_price_with_margin": 115.60616,
          "current_price": 532.59998,
          "fair_value": 144.5077,
          "margin_of_safety": 0.2,
          "margin_to_fv": -2.68562,
          "method": "DCF FCFF TTM; crecimiento limitado y supuestos declarados",
          "source_fields": [
            "free_cash_flow",
            "shares_outstanding",
            "net_debt"
          ],
          "state": "VENTA",
          "upside_to_intrinsic": -0.72867
        },
        "koncorde": {
          "applicable": true,
          "blue": 8.35926,
          "brown": 57.26431,
          "green": 57.17744,
          "red": 80.9148,
          "state": "NEUTRO"
        },
        "macd": {
          "applicable": true,
          "histogram": -1.99525,
          "macd": 6.95797,
          "prev_histogram": -2.30018,
          "signal": 8.95323,
          "state": "NEUTRO"
        },
        "rsi": {
          "applicable": true,
          "prev": 52.61062,
          "rsi14": 57.23897,
          "state": "COMPRA"
        },
        "squeeze": {
          "applicable": true,
          "hist_color": "green",
          "momentum": 7.61981,
          "release_now": false,
          "squeeze_off": false,
          "squeeze_on": true,
          "state": "NEUTRO"
        },
        "tendencia": {
          "applicable": true,
          "ema200": 461.76834,
          "ema50": 506.09285,
          "state": "COMPRA"
        },
        "volume_profile": {
          "applicable": true,
          "counted_volume": 13507531826.0,
          "coverage_sessions": 200,
          "note": "Estimación de volumen por rango de velas; NO VP tick-by-tick ni el indicador original.",
          "poc": 398.8460568745931,
          "state": "COMPRA",
          "vah": 458.5896021525065,
          "val": 366.0291798909505
        }
      },
      "last_complete_session": "2026-10-26",
      "reference_session_date": "2026-10-27",
      "schema_version": "1.0",
      "sell_confluence_pct": 12.5,
      "sessions_loaded": 500,
      "signal_policy": {
        "closed_daily_candles_only": true,
        "equal_weight_applicable_blocks": true,
        "minimum_confluence_pct": 75,
        "missing_applicable_blocks_block_percentage": true,
        "neutral_in_denominator": true
      },
      "symbol": "MSFT",
      "warnings": [
        "Squeeze original LazyBear es la referencia por defecto; corrected=True usa multiplicador BB corregido.",
        "Koncorde reproduce la variante Pine de manboto; no se afirma equivalencia con la versión protegida de Marcos Emmi.",
        "Volume Profile reparte el volumen completo de cada vela en todos los niveles intersectados; no es volumen tick-by-tick.",
        "El porcentaje de confluencia es concordancia de criterios, no probabilidad estadística."
      ]
    }
  ],
  "schema_version": "1.0",
  "symbols": [
    "MSFT"
  ],
  "timezone": "America/New_York",
  "warnings": [
    "Yahoo Finance/yfinance es una fuente gratuita sin SLA; validar cobertura antes de ampliar el universo."
  ]
}
```

<!-- execution_utc: 2026-10-27T15:18:09Z -->
