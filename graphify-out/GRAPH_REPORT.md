# Graph Report - TradingAgentsX  (2026-10-29)

## Corpus Check
- 204 files · ~173,486 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 31 file(s) not represented in the graph (top: (none) 11, .ttf 10, .lock 3)

## Summary
- 2001 nodes · 4590 edges · 121 communities (81 shown, 40 thin omitted)
- Extraction: 96% EXTRACTED · 4% INFERRED · 0% AMBIGUOUS · INFERRED: 172 edges (avg confidence: 0.89)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `ad485912`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- finmind.py
- PDFGenerator
- json
- agents/__init__.py
- cn
- SplashCursor
- prompts.py
- user.py
- YFinanceUtils
- make_cached_system_message
- route_to_vendor
- y_finance.py
- schemas.py
- ApiSettingsDialog.tsx
- os
- TradingService
- AnalysisForm.tsx
- auth-context.tsx
- types.ts
- useLanguage
- Card
- typing
- routes.py
- db/models.py
- history/page.tsx
- HybridSearchEngine
- interface.py
- layout.tsx
- HybridTaskManager
- backend
- storage.ts
- package.json
- dependencies
- ConditionalLogic
- Reflector
- auth_utils.py
- PendingTaskRecovery.tsx
- key_validation_service.py
- redis_client.py
- logging
- components.json
- PriceChart.tsx
- FinancialSituationMemory
- ConfigScreen
- TradingAgentsXGraph
- results/page.tsx
- compilerOptions
- screens/config.py
- LanguageContext.tsx
- DashboardScreen
- TickerCombobox.tsx
- googlenews_utils.py
- run_analysis
- report-utils.ts
- steps
- MessageBuffer
- ProgressTracker
- get_config
- is_redis_available
- global_exception_handler
- constants.py
- Product
- next
- [...path]/route.ts
- CLAUDE.md
- TradingAgentsX - 多代理智能交易分析系統
- TradingAgentsX - Multi-Agent Intelligent Trading Analysis System
- __main__.py
- chat_with_report
- manifest.json
- 2026-10-15T15-38-04Z__frontend-overall-ui.md
- .__init__
- ScrollReveal.tsx
- 📸 應用截圖
- 安裝步驟
- 📸 Application Screenshots
- Installation Steps
- Field
- 📱 使用指南
- 📱 User Guide
- TradingAgentsXApp
- root
- eslint.config.mjs
- cleanup_task
- scripts
- 🤖 AI 代理團隊
- 🤖 AI Agent Team
- 🔒 Security Features
- 🔒 安全特性
- date-fns
- 🔌 API 文檔
- 🔌 API Documentation
- 🛠️ Technology Stack
- 🛠️ 技術棧
- clean_cache.sh
- axios
- class-variance-authority
- clsx
- dexie
- next-themes
- ogl
- @radix-ui/react-dropdown-menu
- @radix-ui/react-popover
- react-day-picker
- react-dom@19.2.0
- @tailwindcss/typography@^0.5.19
- zod
- postcss.config.mjs
- css.d.ts
- tradingagents

## God Nodes (most connected - your core abstractions)
1. `cn()` - 86 edges
2. `useLanguage()` - 49 edges
3. `react` - 48 edges
4. `SplashCursor()` - 44 edges
5. `HistoryPage()` - 39 edges
6. `_make_api_request()` - 37 edges
7. `Button()` - 36 edges
8. `make_cached_system_message()` - 33 edges
9. `FinMindError` - 32 edges
10. `Card()` - 30 edges

## Surprising Connections (you probably didn't know these)
- `Agent Pipeline (LangGraph)` --references--> `RiskDebateState`  [INFERRED]
  CLAUDE.md → tradingagents/agents/utils/agent_states.py
- `LLM Configuration` --references--> `TradingAgentsXGraph`  [INFERRED]
  CLAUDE.md → tradingagents/graph/trading_graph.py
- `Agent Pipeline (LangGraph)` --references--> `TradingAgentsXGraph`  [INFERRED]
  CLAUDE.md → tradingagents/graph/trading_graph.py
- `FinancialSituationMemory` --uses--> `Settings`  [INFERRED]
  tradingagents/agents/utils/memory.py → backend/app/core/config.py
- `TradingService` --uses--> `TradingAgentsXGraph`  [INFERRED]
  backend/app/services/trading_service.py → tradingagents/graph/trading_graph.py

## Import Cycles
- None detected.

## Communities (121 total, 40 thin omitted)

### Community 0 - "finmind.py"
Cohesion: 0.06
Nodes (47): _convert_to_serializable(), _filter_by_date_range(), FinMindAuthenticationError, FinMindDataNotFoundError, FinMindError, FinMindRateLimitError, format_date(), format_output() (+39 more)

### Community 1 - "PDFGenerator"
Cohesion: 0.05
Nodes (5): DownloadService, get_model_display_name(), get_pdf_label(), PDFGenerator, _ReportPDF

### Community 2 - "json"
Cohesion: 0.07
Nodes (24): write_rows(), fetch_json(), load_live_registry(), main(), fetch_sec_tickers(), main(), AlphaVantageRateLimitError, _filter_csv_by_date_range() (+16 more)

### Community 3 - "agents/__init__.py"
Cohesion: 0.08
Nodes (25): create_report_summarizer(), summarizer_node(), create_bear_researcher(), bear_node(), create_bull_researcher(), bull_node(), create_risky_debator(), risky_node() (+17 more)

### Community 4 - "cn"
Cohesion: 0.09
Nodes (32): LoadingSpinner(), LoadingSpinnerProps, buttonVariants, Calendar(), CalendarDayButton(), CardAction(), Checkbox(), DatePicker() (+24 more)

### Community 5 - "SplashCursor"
Cohesion: 0.09
Nodes (39): SplashCursor(), addKeywords(), applyInputs(), calcDeltaTime(), clickSplat(), compileShader(), correctDeltaX(), correctDeltaY() (+31 more)

### Community 6 - "prompts.py"
Cohesion: 0.10
Nodes (18): create_research_manager(), research_manager_node(), create_risk_manager(), risk_manager_node(), create_trader(), trader_node(), get_bear_researcher_prompt(), get_conservative_debator_prompt() (+10 more)

### Community 7 - "user.py"
Cohesion: 0.10
Nodes (17): cleanup_duplicate_reports(), create_report(), delete_all_reports(), delete_report(), get_current_user_optional(), get_current_user_required(), get_report(), get_report_counts() (+9 more)

### Community 8 - "YFinanceUtils"
Cohesion: 0.07
Nodes (8): decorator(), decorate_all_methods(), class_decorator(), get_current_date(), get_next_weekday(), save_output(), init_ticker(), YFinanceUtils

### Community 9 - "make_cached_system_message"
Cohesion: 0.13
Nodes (16): create_fundamentals_analyst(), fundamentals_analyst_node(), create_market_analyst(), market_analyst_node(), create_news_analyst(), news_analyst_node(), create_social_media_analyst(), social_media_analyst_node() (+8 more)

### Community 10 - "route_to_vendor"
Cohesion: 0.09
Nodes (13): get_stock_data(), get_balance_sheet(), get_cashflow(), get_fundamentals(), get_income_statement(), get_global_news(), get_insider_sentiment(), get_insider_transactions() (+5 more)

### Community 11 - "y_finance.py"
Cohesion: 0.10
Nodes (12): log_retry_attempt(), retry(), StockstatsUtils, get_balance_sheet(), get_cashflow(), get_fundamentals(), get_income_statement(), get_insider_transactions() (+4 more)

### Community 12 - "schemas.py"
Cohesion: 0.09
Nodes (15): AnalysisResponse, AnalystReport, ChatRequest, ChatResponse, ConfigResponse, ErrorResponse, HealthResponse, KeyValidationResult (+7 more)

### Community 13 - "ApiSettingsDialog.tsx"
Cohesion: 0.14
Nodes (28): DebateCard(), DebateCardProps, TONE_THEME, ApiSettingsDialog(), formSchema, FormValues, keyValidationMessage(), Dialog() (+20 more)

### Community 14 - "os"
Cohesion: 0.11
Nodes (9): exchange_google_token(), get_current_user(), get_frontend_url(), get_google_client_id(), get_google_client_secret(), google_callback(), google_login(), TokenExchangeRequest (+1 more)

### Community 15 - "TradingService"
Cohesion: 0.09
Nodes (3): get_trading_service(), PriceService, TradingService

### Community 16 - "AnalysisForm.tsx"
Cohesion: 0.15
Nodes (22): AVAILABLE_MODELS, ChatMessage, HistoryChatContent(), HistoryChatPage(), AnalysisForm(), formSchema, MarkdownReportProps, ChatMessage (+14 more)

### Community 17 - "auth-context.tsx"
Cohesion: 0.14
Nodes (27): SyncInitializer(), AuthContext, AuthContextType, AuthProvider(), getAuthHeaders(), getAuthToken(), User, bulkSaveReports() (+19 more)

### Community 18 - "types.ts"
Cohesion: 0.11
Nodes (25): AnalysisFormProps, AGENT_NAME_KEYS, AnalysisProgress(), AnalysisProgressProps, fill(), formatDuration(), api, apiClient (+17 more)

### Community 19 - "useLanguage"
Cohesion: 0.21
Nodes (22): AnalystInfo, DownloadReports(), DownloadReportsProps, GoogleIcon(), LoginButton(), LoginPrompt(), HeroTradingCanvas(), Node (+14 more)

### Community 20 - "Card"
Cohesion: 0.22
Nodes (23): AgentCard(), FeatureCard(), HomePage(), LLMProviderCard(), SectionHeading(), TechnicalCard(), WorkflowStep(), AgentCard() (+15 more)

### Community 21 - "typing"
Cohesion: 0.15
Nodes (4): InvestDebateState, RiskDebateState, Propagator, SignalProcessor

### Community 22 - "routes.py"
Cohesion: 0.11
Nodes (9): download_reports(), generate_pdf_temp(), run_analysis(), report_progress(), run_background_analysis(), _schedule_pdf_cleanup(), validate_keys(), AnalysisRequest (+1 more)

### Community 23 - "db/models.py"
Cohesion: 0.11
Nodes (8): Base, check_db_connection(), get_db(), init_db(), Report, User, UserSettings, startup_event()

### Community 24 - "history/page.tsx"
Cohesion: 0.13
Nodes (21): ANALYSTS, detectReportLanguage(), extractDecisionFromReport(), getMarketLabels(), getReportSignature(), HistoryPage(), parseUTCDate(), TradingDecisionProps (+13 more)

### Community 25 - "HybridSearchEngine"
Cohesion: 0.10
Nodes (3): Settings, Config, HybridSearchEngine

### Community 26 - "interface.py"
Cohesion: 0.13
Nodes (12): get_data_in_range(), get_finnhub_company_insider_sentiment(), get_finnhub_company_insider_transactions(), get_finnhub_news(), get_reddit_company_news(), get_reddit_global_news(), get_simfin_balance_sheet(), get_simfin_cashflow() (+4 more)

### Community 27 - "layout.tsx"
Cohesion: 0.13
Nodes (13): inter, metadata, RootLayout(), CustomCursor(), Footer(), hexToVec3(), SoftAurora(), SoftAurora (+5 more)

### Community 29 - "backend"
Cohesion: 0.09
Nodes (24): build, container_name, environment, networks, ports, restart, volumes, context (+16 more)

### Community 30 - "storage.ts"
Cohesion: 0.17
Nodes (23): clearCryptoData(), decrypt(), decryptObject(), deriveKey(), encrypt(), encryptObject(), generateSalt(), getBrowserFingerprint() (+15 more)

### Community 31 - "package.json"
Cohesion: 0.12
Nodes (23): devDependencies, babel-plugin-react-compiler@1.0.0, baseline-browser-mapping@^2.9.2, tailwindcss@^4, @tailwindcss/postcss@^4, tw-animate-css@^1.4.0, @types/node@^20, @types/react@^19 (+15 more)

### Community 32 - "dependencies"
Cohesion: 0.08
Nodes (24): dependencies, @hookform/resolvers@^5.2.2, lucide-react@^0.554.0, next@16.0.10, @radix-ui/react-checkbox@^1.3.3, @radix-ui/react-dialog@^1.1.15, @radix-ui/react-label@^2.1.8, @radix-ui/react-select@^2.2.6 (+16 more)

### Community 33 - "ConditionalLogic"
Cohesion: 0.11
Nodes (3): AgentState, ConditionalLogic, GraphSetup

### Community 35 - "auth_utils.py"
Cohesion: 0.11
Nodes (7): get_current_user_optional(), get_current_user_required(), user_events(), create_access_token(), _get_fernet_key(), get_user_id_from_token(), verify_access_token()

### Community 36 - "PendingTaskRecovery.tsx"
Cohesion: 0.20
Nodes (16): AnalysisPage(), AuthCallbackContent(), AuthCallbackPage(), LoadingFallback(), PendingTaskRecovery(), ErrorAlert(), ErrorAlertProps, useAuth() (+8 more)

### Community 37 - "key_validation_service.py"
Cohesion: 0.18
Nodes (8): _check_alpha_vantage(), _check_anthropic(), _check_finmind(), _check_google(), _check_openai_compatible(), _result(), validate_api_keys(), test()

### Community 38 - "redis_client.py"
Cohesion: 0.14
Nodes (9): cache_delete(), cache_get(), cache_set(), check_rate_limit(), delete_task_from_redis(), get_redis_client(), get_task_from_redis(), save_task_to_redis() (+1 more)

### Community 39 - "logging"
Cohesion: 0.14
Nodes (3): extract_tickers(), tokenize_financial_text(), HybridFinancialMemory

### Community 40 - "components.json"
Cohesion: 0.10
Nodes (19): aliases, components, hooks, lib, ui, utils, iconLibrary, registries (+11 more)

### Community 41 - "PriceChart.tsx"
Cohesion: 0.22
Nodes (17): AnalystReport(), AnalystReportProps, extractLastRound(), ReportSection(), calculateHeikinAshi(), HeikinAshiCandlestickShape(), HeikinAshiCandlestickShapeProps, HeikinAshiData (+9 more)

### Community 43 - "ConfigScreen"
Cohesion: 0.16
Nodes (6): on, schedule, workflow_dispatch, cron, embedding_models_for(), ConfigScreen

### Community 44 - "TradingAgentsXGraph"
Cohesion: 0.12
Nodes (7): Agent Pipeline (LangGraph), Architecture, Backend Service Layer, Data Sources (tradingagents/dataflows/), Frontend Architecture, LLM Configuration, TradingAgentsXGraph

### Community 45 - "results/page.tsx"
Cohesion: 0.18
Nodes (16): AnalysisResultsPage(), ANALYST_REPORT_KEYS, asContent(), getNestedValue(), DebateTone, FullReport(), FullReportProps, FullReportSection (+8 more)

### Community 46 - "compilerOptions"
Cohesion: 0.11
Nodes (18): compilerOptions, allowJs, esModuleInterop, incremental, isolatedModules, jsx, lib, module (+10 more)

### Community 48 - "LanguageContext.tsx"
Cohesion: 0.19
Nodes (14): getServerSnapshot(), getStoredLocale(), LanguageContext, LanguageContextType, LanguageProvider(), subscribeToStorage(), useTranslation(), en (+6 more)

### Community 50 - "TickerCombobox.tsx"
Cohesion: 0.23
Nodes (14): TickerCombobox(), TickerComboboxProps, displayName(), loadStocks(), loadTw(), loadUs(), lookupStockName(), MarketType (+6 more)

### Community 51 - "googlenews_utils.py"
Cohesion: 0.17
Nodes (5): get_global_news_google(), get_google_news(), getNewsData(), is_rate_limited(), make_request()

### Community 52 - "run_analysis"
Cohesion: 0.15
Nodes (7): build_config(), run_analysis(), save_message_decorator(), wrapper(), save_report_section_decorator(), save_tool_call_decorator(), _content_to_str()

### Community 53 - "report-utils.ts"
Cohesion: 0.19
Nodes (12): DEBATE_ROUND_PREFIXES, decision(), DecisionSource, extractDecisionFromResult(), ExtractedDecision, findFinalProposal(), findOtherDecision(), getReportSignature() (+4 more)

### Community 54 - "steps"
Cohesion: 0.13
Nodes (14): SEC_CONTACT, jobs, refresh, name, permissions, contents, runs-on, steps (+6 more)

### Community 57 - "get_config"
Cohesion: 0.15
Nodes (4): get_config(), get_task_status(), get_tickers(), serve_pdf_temp()

### Community 58 - "is_redis_available"
Cohesion: 0.15
Nodes (3): health_check(), is_redis_available(), cleanup_worker()

### Community 59 - "global_exception_handler"
Cohesion: 0.17
Nodes (3): global_exception_handler(), RateLimitMiddleware, SecurityHeadersMiddleware

### Community 60 - "constants.py"
Cohesion: 0.23
Nodes (4): env_api_key_for_model(), env_api_key_for_provider(), infer_provider_from_model(), AnalystType

### Community 61 - "Product"
Cohesion: 0.17
Nodes (11): Accessibility & Inclusion, Brand Commitments, Capabilities and Constraints, Evidence on Hand, Operating Context, Platform, Positioning, Product (+3 more)

### Community 62 - "next"
Cohesion: 0.20
Nodes (4): GET(), getBaseUrl(), nextConfig, next

### Community 63 - "[...path]/route.ts"
Cohesion: 0.25
Nodes (8): POST(), DELETE, GET, PATCH, POST, proxyRequest(), PUT, getBackendUrl()

### Community 64 - "CLAUDE.md"
Cohesion: 0.20
Nodes (8): Backend (Python 3.10+), Commands, Docker (full stack), Frontend (Next.js), Important Notes, Key Environment Variables, Project Overview, TypeScript type checking

### Community 65 - "TradingAgentsX - 多代理智能交易分析系統"
Cohesion: 0.20
Nodes (9): 🐳 Docker 部署, 📄 License, TradingAgentsX - 多代理智能交易分析系統, 專案結構, 整體系統架構圖, 🎯 核心特色, 📖 簡介, 🏗️ 系統架構 (+1 more)

### Community 66 - "TradingAgentsX - Multi-Agent Intelligent Trading Analysis System"
Cohesion: 0.20
Nodes (9): 🙏 Acknowledgements, 🎯 Core Features, 🐳 Docker Deployment, 📖 Introduction, 📄 License, Overall System Architecture Diagram, Project Structure, 🏗️ System Architecture (+1 more)

### Community 68 - "chat_with_report"
Cohesion: 0.28
Nodes (3): chat_with_report(), chat_with_reports(), _flatten_reports()

### Community 69 - "manifest.json"
Cohesion: 0.22
Nodes (8): background_color, description, display, icons, name, short_name, start_url, theme_color

### Community 70 - "2026-10-15T15-38-04Z__frontend-overall-ui.md"
Cohesion: 0.22
Nodes (8): Design Health Score, Design Specificity Verdict, Minor Observations, Overall Impression, Persona Red Flags, Priority Issues, Questions to Consider, What's Working

### Community 72 - "ScrollReveal.tsx"
Cohesion: 0.46
Nodes (7): apply(), clamp(), easeOut(), items, onScroll(), ScrollReveal(), tick()

### Community 73 - "📸 應用截圖"
Cohesion: 0.25
Nodes (8): 12位分析師報告, API 配置頁面, PDF報告預覽與下載, 任務配置頁面, 分析歷史, 報告AI問答, 📸 應用截圖, 首頁

### Community 74 - "安裝步驟"
Cohesion: 0.25
Nodes (8): 1️⃣ 克隆專案, 2️⃣ 後端設置, 3️⃣ 前端設置, 4️⃣ 終端機介面（TUI，選用）, 前置要求, 安裝步驟, 必要的 API 金鑰, 🚀 快速開始

### Community 75 - "📸 Application Screenshots"
Cohesion: 0.25
Nodes (8): 12 Analyst Reports, AI Report Q&A, Analysis History, API Configuration Page, 📸 Application Screenshots, Home Page, PDF Report Preview and Download, Task Configuration Page

### Community 76 - "Installation Steps"
Cohesion: 0.25
Nodes (8): 1️⃣ Clone the Repository, 2️⃣ Backend Setup, 3️⃣ Frontend Setup, 4️⃣ Terminal UI (TUI, optional), Installation Steps, Prerequisites, 🚀 Quick Start, Required API Keys

### Community 79 - "📱 使用指南"
Cohesion: 0.29
Nodes (7): 1. 配置 API 金鑰, 2. 選擇分析參數, 3. 執行分析, 4. 查看結果, 5. 儲存與下載, 📱 使用指南, 📄 範例報告

### Community 80 - "📱 User Guide"
Cohesion: 0.29
Nodes (7): 1. Configure API Keys, 2. Select Analysis Parameters, 3. Run Analysis, 4. View Results, 5. Save and Download, 📄 Sample Report, 📱 User Guide

### Community 83 - "eslint.config.mjs"
Cohesion: 0.33
Nodes (5): eslintConfig, eslint@^9, eslint-config-next@16.0.3, eslint, eslint-config-next

### Community 85 - "scripts"
Cohesion: 0.40
Nodes (5): scripts, build, dev, lint, start

### Community 86 - "🤖 AI 代理團隊"
Cohesion: 0.40
Nodes (5): 🤖 AI 代理團隊, 交易與風險團隊 (5 位), 分析師團隊 (4 位), 報告整合 (1 位), 研究團隊 (3 位)

### Community 87 - "🤖 AI Agent Team"
Cohesion: 0.40
Nodes (5): 🤖 AI Agent Team, Analyst Team (4 Agents), Report Synthesis (1 Agent), Research Team (3 Agents), Trading & Risk Team (5 Agents)

### Community 88 - "🔒 Security Features"
Cohesion: 0.40
Nodes (5): Backend Security, Cloud Sync, Frontend Security, Local Development vs. Production Environment, 🔒 Security Features

### Community 89 - "🔒 安全特性"
Cohesion: 0.40
Nodes (5): 前端安全, 🔒 安全特性, 後端安全, 本地開發 vs 生產環境, 雲端同步

### Community 90 - "date-fns"
Cohesion: 0.33
Nodes (4): date-fns@^4.1.0, @radix-ui/react-slot@^1.2.4, date-fns, @radix-ui/react-slot

### Community 91 - "🔌 API 文檔"
Cohesion: 0.50
Nodes (4): 🔌 API 文檔, 健康檢查, 執行分析, 查詢任務狀態

### Community 92 - "🔌 API Documentation"
Cohesion: 0.50
Nodes (4): 🔌 API Documentation, Health Check, Query Task Status, Run Analysis

### Community 93 - "🛠️ Technology Stack"
Cohesion: 0.67
Nodes (3): Backend, Frontend, 🛠️ Technology Stack

### Community 94 - "🛠️ 技術棧"
Cohesion: 0.67
Nodes (3): 前端, 後端, 🛠️ 技術棧

## Knowledge Gaps
- **1 isolated node(s):** `tradingagents`
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 795 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **40 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `react` connect `cn` to `dependencies`, `PendingTaskRecovery.tsx`, `ScrollReveal.tsx`, `PriceChart.tsx`, `results/page.tsx`, `ApiSettingsDialog.tsx`, `AnalysisForm.tsx`, `auth-context.tsx`, `types.ts`, `useLanguage`, `TickerCombobox.tsx`, `Card`, `LanguageContext.tsx`, `history/page.tsx`, `layout.tsx`, `package.json`?**
  _High betweenness centrality (0.021) - this node is a cross-community bridge._
- **Are the 5 inferred relationships involving `SplashCursor()` (e.g. with `handleMouseDown()` and `handleMouseMove()`) actually correct?**
  _`SplashCursor()` has 5 INFERRED edges - model-reasoned connections that need verification._
- **What connects `tradingagents` to the rest of the system?**
  _1 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `finmind.py` be split into smaller, more focused modules?**
  _Cohesion score 0.06444444444444444 - nodes in this community are weakly interconnected._
- **Why does `TradingAgentsXGraph` connect `TradingAgentsXGraph` to `ConditionalLogic`, `Reflector`, `.__init__`, `FinancialSituationMemory`, `analysis.py`, `TradingService`, `run_analysis`, `typing`, `ProgressTracker`?**
  _High betweenness centrality (0.020) - this node is a cross-community bridge._
- **Should `PDFGenerator` be split into smaller, more focused modules?**
  _Cohesion score 0.051643192488262914 - nodes in this community are weakly interconnected._
- **Should `json` be split into smaller, more focused modules?**
  _Cohesion score 0.06605222734254992 - nodes in this community are weakly interconnected._