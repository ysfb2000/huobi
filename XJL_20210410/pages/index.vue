<template>
<div class="container">
    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#" id="nav-button">
      <span>
        <img src="~/assets/css/navbar.png" alt="Navbar">
      </span>
    </a>
    <header>
      <div class="flex_box">
        <img src="~/assets/css/logo.svg" class="logo" alt="Logo">
        <div class="nav_box">
          <span class="nav_cell" style="display: none">
            <a href="javascript:;" class="nav_first">v1<i class="icon_nav"></i></a>
            <ul class="nav_ul">
              <li>
                <a href="https://huobiapi.github.io/docs/spot/v1/en/" id="v1_url">v1</a>
              </li>
            </ul>
          </span>
          <span class="nav_cell nav_tab">
            <a href="https://huobiapi.github.io/docs/spot/v1/en/" id="btn_spot" class="">Spot</a>
          </span>
          <span class="nav_cell nav_tab">
            <a href="https://huobiapi.github.io/docs/dm/v1/en/" id="btn_dm" class="">Futures</a>
          </span>
          <span class="nav_cell nav_tab">
            <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/" id="btn_coin_margined_swap" class="current">Coin Margined Swap</a>
          </span>
          <span class="nav_cell nav_tab">
            <a href="https://huobiapi.github.io/docs/usdt_swap/v1/en/" id="btn_usdt_swap" class="">USDT Margined Swap</a>
          </span>
          <span class="nav_cell nav_tab">
            <a href="https://huobiapi.github.io/docs/option/v1/en/" id="btn_option" class="">Option</a>
          </span>
          <!-- <span class="nav_cell nav_tab">
            <a href="/docs/swap/v1/en/" id="btn_swap">永续合约</a>
          </span> -->
        </div>
      </div>
      <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/cn/" class="lang" id="lang_box" style="display: block;">中文</a>
    </header>
    <div class="toc-wrapper">
        <div class="lang-selector">
              <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#" data-language-name="shell" class="active">shell</a>
        </div>
        <div class="search">
          <input type="text" class="search" id="input-search" placeholder="Search">
        </div>
        <ul class="search-results"></ul>
      <ul id="toc" class="toc-list-h1">
          <li>
            <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#introduction" class="toc-h1 toc-link active" data-title="Introduction">Introduction</a>
              <ul class="toc-list-h2 active" style="display: block;">
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#api-documentation-summary" class="toc-h2 toc-link" data-title="API Documentation Summary">API Documentation Summary</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#market-maker-program" class="toc-h2 toc-link" data-title="Market Maker Program">Market Maker Program</a>
                  </li>
              </ul>
          </li>
          <li>
            <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#changelog" class="toc-h1 toc-link" data-title="Changelog">Changelog</a>
              <ul class="toc-list-h2">
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#1-1-6-2021-2-26-added-query-asset-valuation-interface-query-a-batch-of-funding-rate-interface-modified-query-swap-price-limitation-interface-support-users-not-to-fill-in-all-input-parameters-and-the-interface-returns-the-price-limit-data-of-all-available-contracts-modified-query-the-last-trade-of-a-contract-interface-support-users-not-to-fill-in-all-input-parameters-the-interface-returns-the-latest-transaction-data-of-all-available-contracts-and-in-that-case-the-return-parameter-quot-ch-quot-value-is-quot-market-trade-detail-quot-added-one-field-in-return-quot-tick-quot-parameter-quot-contract_code-quot" class="toc-h2 toc-link" data-title="1.1.6 2021-2-26 【Added: Query Asset Valuation interface, Query a Batch of Funding Rate interface. Modified Query Swap Price Limitation interface(Support users not to fill in all input parameters, and the interface returns the price limit data of all available contracts). Modified Query The Last Trade of a Contract interface(Support users not to fill in all input parameters, the interface returns the latest transaction data of all available contracts; And in that case, the return parameter "  parameter:="">1.1.6 2021-2-26 【Added: Query Asset Valuation interface, Query a Batch of Funding Rate interface. Modified Query Swap Price Limitation interface(Support users not to fill in all input parameters, and the interface returns the price limit data of all available contracts). Modified Query The Last Trade of a Contract interface(Support users not to fill in all input parameters, the interface returns the latest transaction data of all available contracts; And in that case, the return parameter "ch" value is "market.*trade.detail". Added one field in return "tick" parameter: "contract_code")】</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#1-1-5-2021-2-5-added-query-information-on-tiered-margin-set-a-batch-of-sub-account-trading-permissions-query-a-batch-of-sub-account-39-s-assets-information-4-7-modified-the-existing-interfaces-and-added-new-parameters-8-query-user-s-settlement-records-interface-to-avoid-affecting-system-performance-the-interface-only-supports-querying-user-settlement-records-in-the-last-90-days" class="toc-h2 toc-link" data-title="1.1.5 2021-2-5 【Added: Query information on Tiered Margin. Set a Batch of Sub-Account Trading Permissions. Query a Batch of Sub-Account&#39;s Assets Information. 4-7 Modified the existing interfaces and added new parameters. 8 Query user’s settlement records interface(To avoid affecting system performance, the interface only supports querying user settlement records in the last 90 days)】">1.1.5 2021-2-5 【Added: Query information on Tiered Margin. Set a Batch of Sub-Account Trading Permissions. Query a Batch of Sub-Account's Assets Information. 4-7 Modified the existing interfaces and added new parameters. 8 Query user’s settlement records interface(To avoid affecting system performance, the interface only supports querying user settlement records in the last 90 days)】</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#1-1-4-2021-1-29-added-get-a-batch-of-market-data-overview-get-kline-data-of-mark-price-subscribe-kline-data-of-mark-price-request-kline-data-of-mark-price-5-17-added-fields-to-modify-interface-the-order_id-of-submitted-trigger-order-response-has-been-changed-from-the-original-natural-number-self-incrementing-id-to-a-unique-identification-id-with-a-length-of-18-digits-it-is-recommended-to-use-the-order_id_str-order_id-in-string-type-of-submitted-order-response-to-avoid-the-occurrence-of-truncation-by-the-system-because-excessive-length" class="toc-h2 toc-link" data-title="1.1.4 2021-1-29 【Added:Get a Batch of Market Data Overview、Get Kline Data of Mark Price、Subscribe Kline Data of Mark Price、Request Kline Data of Mark Price. 5-17 Added fields to modify interface. The order_id of submitted trigger order response has been changed from the original natural number self-incrementing ID to a unique identification ID with a length of 18 digits. It is recommended to use the order_id_str (order_id in string type) of submitted order response  to avoid the occurrence of truncation by the system because excessive length.】">1.1.4 2021-1-29 【Added:Get a Batch of Market Data Overview、Get Kline Data of Mark Price、Subscribe Kline Data of Mark Price、Request Kline Data of Mark Price. 5-17 Added fields to modify interface. The order_id of submitted trigger order response has been changed from the original natural number self-incrementing ID to a unique identification ID with a length of 18 digits. It is recommended to use the order_id_str (order_id in string type) of submitted order response  to avoid the occurrence of truncation by the system because excessive length.】</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#1-1-3-2021-01-12-1-added-get-the-estimated-settlement-price-2-7-added-set-a-take-profit-and-stop-loss-order-interfaces-8-21-added-fields-to-modify-interface-added-the-first-level-menu-of-contract-trigger-order-and-add-take-profit-and-stop-loss-related-interfaces-and-move-the-original-contract-trigger-order-related-interfaces-to-this-menu" class="toc-h2 toc-link" data-title="1.1.3 2021-01-12 【1 Added Get the estimated settlement price. 2-7 Added ”Set a Take-profit and Stop-loss Order“ interfaces. 8-21 Added fields to modify interface. Added the first-level menu of [Contract Trigger Order], and add take-profit and stop-loss related interfaces and move the original contract trigger order related interfaces to this menu 】">1.1.3 2021-01-12 【1 Added Get the estimated settlement price. 2-7 Added ”Set a Take-profit and Stop-loss Order“ interfaces. 8-21 Added fields to modify interface. Added the first-level menu of [Contract Trigger Order], and add take-profit and stop-loss related interfaces and move the original contract trigger order related interfaces to this menu 】</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#1-1-2-2020-12-02-modified-order-details-acquisition-interface-when-querying-cancelation-data-of-orders-that-have-not-been-partially-filled-if-created_at-and-order_type-parameters-are-not-uploaded-the-data-that-can-be-queried-reduced-from-last-12-hours-to-last-2-hours-modified-query-history-orders-interface-when-querying-cancelation-data-of-orders-that-have-not-been-partially-filled-the-data-that-can-be-retained-reduced-from-last-24-hours-to-last-2-hours-modified-query-history-orders-via-multiple-fields-interface-when-querying-cancelation-data-of-orders-that-have-not-been-partially-filled-the-data-that-can-be-retained-reduced-from-last-24-hours-to-last-2-hours" class="toc-h2 toc-link" data-title="1.1.2 2020-12-02 【Modified “Order details acquisition” interface (When querying cancelation data of orders that have not been partially filled, if “created_at” and “order_type” parameters are not uploaded, the data that can be queried reduced from last 12 hours to last 2 hours.); modified “Query history orders” interface (When querying cancelation data of orders that have not been partially filled, the data that can be retained reduced from last 24 hours to last 2 hours.); modified “Query history orders via multiple fields” interface (When querying cancelation data of orders that have not been partially filled, the data that can be retained reduced from last 24 hours to last 2 hours.)】">1.1.2 2020-12-02 【Modified “Order details acquisition” interface (When querying cancelation data of orders that have not been partially filled, if “created_at” and “order_type” parameters are not uploaded, the data that can be queried reduced from last 12 hours to last 2 hours.); modified “Query history orders” interface (When querying cancelation data of orders that have not been partially filled, the data that can be retained reduced from last 24 hours to last 2 hours.); modified “Query history orders via multiple fields” interface (When querying cancelation data of orders that have not been partially filled, the data that can be retained reduced from last 24 hours to last 2 hours.)】</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#1-1-1-2020-11-24-added-query-historical-settlement-records-of-the-platform-interface-modified-added-fields-of-return-parameter-for-quot-query-liquidation-orders-quot-interface-and-quot-subscribe-liquidation-order-data-quot-interface" class="toc-h2 toc-link" data-title="1.1.1 2020-11-24 【Added: Query historical settlement records of the platform interface. Modified:  Added fields of return parameter for " query="" liquidation="">1.1.1 2020-11-24 【Added: Query historical settlement records of the platform interface. Modified:  Added fields of return parameter for "Query Liquidation Orders" interface and "Subscribe Liquidation Order Data" interface】</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#1-1-0-2020-10-28-newly-added-query-financial-records-via-multiple-fields-query-history-orders-via-multiple-fields-query-history-transactions-via-multiple-fields" class="toc-h2 toc-link" data-title="1.1.0 2020-10-28 【Newly added：Query financial records via multiple fields, Query history orders via multiple fields,Query history transactions via multiple fields.】">1.1.0 2020-10-28 【Newly added：Query financial records via multiple fields, Query history orders via multiple fields,Query history transactions via multiple fields.】</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#1-0-9-2020-10-15-newly-added-added-switch-leverage-interface-updated-websocket-messages-of-account-topic-will-be-pushed-when-leverage-switch-succeeds-websocket-messages-of-position-topic-will-be-pushed-when-leverage-switch-succeeds-new-response-fields-are-added-on-websocket-topic-of-match-orders-the-interface-swap_order_info-supports-query-of-4-hour-order-cancellation-data-previously-only-support-to-query-24-hour-data" class="toc-h2 toc-link" data-title="1.0.9 2020-10-15 【Newly added：Added switch leverage interface; Updated:  websocket messages of account topic will be pushed when leverage switch succeeds;  websocket messages of position topic will be pushed when leverage switch succeeds; new response fields are added on websocket topic of match orders; the interface(swap_order_info) supports query of 4-hour order cancellation data (previously only support to query 24-hour data).】">1.0.9 2020-10-15 【Newly added：Added switch leverage interface; Updated:  websocket messages of account topic will be pushed when leverage switch succeeds;  websocket messages of position topic will be pushed when leverage switch succeeds; new response fields are added on websocket topic of match orders; the interface(swap_order_info) supports query of 4-hour order cancellation data (previously only support to query 24-hour data).】</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#1-0-8-2020-10-10-newly-added-added-ws-interface-for-subscribing-system-status-updates-push" class="toc-h2 toc-link" data-title="1.0.8 2020-10-10 【Newly added：Added WS interface for subscribing system status updates push】">1.0.8 2020-10-10 【Newly added：Added WS interface for subscribing system status updates push】</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#1-0-7-2020-08-06-added-interfaces-subscribe-market-bbo-data-push-query-user-s-available-leverage-query-user-s-settlement-records-subscribe-trigger-orders-updates" class="toc-h2 toc-link" data-title="1.0.7 2020-08-06 【Added interfaces：Subscribe market BBO data push； Query user’s available leverage；Query user’s settlement records；Subscribe trigger orders updates 】">1.0.7 2020-08-06 【Added interfaces：Subscribe market BBO data push； Query user’s available leverage；Query user’s settlement records；Subscribe trigger orders updates 】</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#1-0-6-2020-06-19-update-added-client_order_id-in-outer-return-parameter" class="toc-h2 toc-link" data-title="1.0.6 2020-06-19 【 Update: added client_order_id in outer return parameter 】">1.0.6 2020-06-19 【 Update: added client_order_id in outer return parameter 】</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#1-0-5-2020-06-14-add-interfaces-premium-index-kline-data-websocket-restful-estimated-funding-rate-kline-data-restful-websocket-basis-data-restful-websocket-update-interfaces-add-average-premium-index-of-querying-historical-funding-rates-add-four-depth-level-of-subscribing-market-depth-etc" class="toc-h2 toc-link" data-title="1.0.5 2020-06-14  【 Add interfaces: Premium index Kline data(websocket, restful); Estimated funding rate Kline data(restful, websocket); Basis data (restful, websocket);Update interfaces: add average premium index of querying historical funding rates; add four depth level of subscribing market depth; etc】">1.0.5 2020-06-14  【 Add interfaces: Premium index Kline data(websocket, restful); Estimated funding rate Kline data(restful, websocket); Basis data (restful, websocket);Update interfaces: add average premium index of querying historical funding rates; add four depth level of subscribing market depth; etc】</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#1-0-4-2020-5-27-add-an-interface-websocket-subscription-of-contract-info" class="toc-h2 toc-link" data-title="1.0.4 2020-5-27 【 Add an interface: websocket subscription of contract info 】">1.0.4 2020-5-27 【 Add an interface: websocket subscription of contract info 】</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#1-0-3-2020-05-07-add-an-interface-query-assets-and-position-info" class="toc-h2 toc-link" data-title="1.0.3 2020-05-07 【 Add an interface: query assets and position info】">1.0.3 2020-05-07 【 Add an interface: query assets and position info】</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#1-0-2-2020-04-09-add-an-interface-perpetual-swaps-funding-rate-ws-push-without-authentication-2-add-an-interface-perpetual-swaps-liquidation-order-ws-push-without-authentication" class="toc-h2 toc-link" data-title="1.0.2 2020-04-09 [Add an interface: perpetual swaps funding rate WS push without authentication;2.   Add an interface: perpetual swaps liquidation order WS push without authentication]">1.0.2 2020-04-09 [Add an interface: perpetual swaps funding rate WS push without authentication;2.   Add an interface: perpetual swaps liquidation order WS push without authentication]</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#1-0-1-2020-03-20" class="toc-h2 toc-link" data-title="1.0.1 2020-03-20">1.0.1 2020-03-20</a>
                  </li>
              </ul>
          </li>
          <li>
            <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#swap-api-access-guide" class="toc-h1 toc-link" data-title="Swap API Access Guide">Swap API Access Guide</a>
              <ul class="toc-list-h2">
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#api-list" class="toc-h2 toc-link" data-title="API List">API List</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#address" class="toc-h2 toc-link" data-title="Address">Address</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#signature-authentication-amp-verification" class="toc-h2 toc-link" data-title="Signature Authentication &amp; Verification">Signature Authentication &amp; Verification</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#api-rate-limit-illustration" class="toc-h2 toc-link" data-title="API Rate Limit Illustration">API Rate Limit Illustration</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#api-limitation-on-order-cancellation-ratio" class="toc-h2 toc-link" data-title="API Limitation on Order Cancellation Ratio">API Limitation on Order Cancellation Ratio</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#maintenance-with-service-suspended" class="toc-h2 toc-link" data-title="Maintenance with service suspended">Maintenance with service suspended</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#get-system-status" class="toc-h2 toc-link" data-title="Get system status">Get system status</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-whether-the-system-is-available" class="toc-h2 toc-link" data-title="Query whether the system is available">Query whether the system is available</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#get-current-system-timestamp" class="toc-h2 toc-link" data-title="Get current system timestamp">Get current system timestamp</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#details-of-each-error-code" class="toc-h2 toc-link" data-title="Details of Each Error Code">Details of Each Error Code</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#api-best-practice" class="toc-h2 toc-link" data-title="API Best Practice">API Best Practice</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#code-demo" class="toc-h2 toc-link" data-title="Code Demo">Code Demo</a>
                  </li>
              </ul>
          </li>
          <li>
            <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#swap-api-faq" class="toc-h1 toc-link" data-title="Swap API FAQ">Swap API FAQ</a>
              <ul class="toc-list-h2">
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#access-and-authentication" class="toc-h2 toc-link" data-title="Access and Authentication">Access and Authentication</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#market-and-websocket" class="toc-h2 toc-link" data-title="Market and Websocket">Market and Websocket</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#order-and-trade" class="toc-h2 toc-link" data-title="Order and Trade">Order and Trade</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#error-codes" class="toc-h2 toc-link" data-title="Error Codes">Error Codes</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#how-to-solve-problems-more-effectively" class="toc-h2 toc-link" data-title="How to solve problems more effectively?">How to solve problems more effectively?</a>
                  </li>
              </ul>
          </li>
          <li>
            <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#swap-market-data-interface" class="toc-h1 toc-link" data-title="Swap Market Data interface">Swap Market Data interface</a>
              <ul class="toc-list-h2">
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-swap-info" class="toc-h2 toc-link" data-title="Query Swap Info">Query Swap Info</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-swap-index-price-information" class="toc-h2 toc-link" data-title="Query Swap Index Price Information">Query Swap Index Price Information</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-swap-price-limitation" class="toc-h2 toc-link" data-title="Query Swap Price Limitation">Query Swap Price Limitation</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#get-swap-open-interest-information" class="toc-h2 toc-link" data-title="Get Swap Open Interest Information">Get Swap Open Interest Information</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#get-market-depth" class="toc-h2 toc-link" data-title="Get Market Depth">Get Market Depth</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#get-kline-data" class="toc-h2 toc-link" data-title="Get KLine Data">Get KLine Data</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#get-kline-data-of-mark-price" class="toc-h2 toc-link" data-title="Get Kline Data of Mark Price">Get Kline Data of Mark Price</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#get-market-data-overview" class="toc-h2 toc-link" data-title="Get Market Data Overview">Get Market Data Overview</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#get-a-batch-of-market-data-overview" class="toc-h2 toc-link" data-title="Get a Batch of Market Data Overview">Get a Batch of Market Data Overview</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-the-last-trade-of-a-contract" class="toc-h2 toc-link" data-title="Query The Last Trade of a Contract">Query The Last Trade of a Contract</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-a-batch-of-trade-records-of-a-contract" class="toc-h2 toc-link" data-title="Query a Batch of Trade Records of a Contract">Query a Batch of Trade Records of a Contract</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-information-on-contract-insurance-fund-balance-and-estimated-clawback-rate" class="toc-h2 toc-link" data-title="Query information on contract insurance fund balance and estimated clawback rate">Query information on contract insurance fund balance and estimated clawback rate</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-history-records-of-insurance-fund-balance" class="toc-h2 toc-link" data-title="Query history records of insurance fund balance">Query history records of insurance fund balance</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-information-on-tiered-adjustment-factor" class="toc-h2 toc-link" data-title="Query information on Tiered Adjustment Factor">Query information on Tiered Adjustment Factor</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-information-on-open-interest" class="toc-h2 toc-link" data-title="Query information on open interest">Query information on open interest</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-information-on-tiered-margin-interface" class="toc-h2 toc-link" data-title="Query information on Tiered Margin interface">Query information on Tiered Margin interface</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-information-on-system-status" class="toc-h2 toc-link" data-title="Query information on system status">Query information on system status</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-top-trader-sentiment-index-function-account" class="toc-h2 toc-link" data-title="Query Top Trader Sentiment Index Function-Account">Query Top Trader Sentiment Index Function-Account</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-top-trader-sentiment-index-function-position" class="toc-h2 toc-link" data-title="Query Top Trader Sentiment Index Function-Position">Query Top Trader Sentiment Index Function-Position</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#get-the-estimated-settlement-price" class="toc-h2 toc-link" data-title="Get the estimated settlement price">Get the estimated settlement price</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-liquidation-orders" class="toc-h2 toc-link" data-title="Query Liquidation Orders">Query Liquidation Orders</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-historical-settlement-records-of-the-platform-interface" class="toc-h2 toc-link" data-title="Query historical settlement records of the platform interface">Query historical settlement records of the platform interface</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-funding-rate" class="toc-h2 toc-link" data-title="Query funding rate">Query funding rate</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-a-batch-of-funding-rate" class="toc-h2 toc-link" data-title="Query a Batch of Funding Rate">Query a Batch of Funding Rate</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-historical-funding-rate" class="toc-h2 toc-link" data-title="Query historical funding rate">Query historical funding rate</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-premium-index-kline-data" class="toc-h2 toc-link" data-title="Query Premium Index Kline Data">Query Premium Index Kline Data</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-estimated-funding-rate-kline-data" class="toc-h2 toc-link" data-title="Query Estimated Funding Rate Kline Data">Query Estimated Funding Rate Kline Data</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-basis-data" class="toc-h2 toc-link" data-title="Query Basis Data">Query Basis Data</a>
                  </li>
              </ul>
          </li>
          <li>
            <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#swap-account-interface" class="toc-h1 toc-link" data-title="Swap Account Interface">Swap Account Interface</a>
              <ul class="toc-list-h2">
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-asset-valuation" class="toc-h2 toc-link" data-title="Query Asset Valuation">Query Asset Valuation</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-user-s-account-information" class="toc-h2 toc-link" data-title="Query User’s Account Information">Query User’s Account Information</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-user-s-position-information" class="toc-h2 toc-link" data-title="Query User’s Position Information">Query User’s Position Information</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-assets-and-positions" class="toc-h2 toc-link" data-title="Query Assets And Positions">Query Assets And Positions</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#set-a-batch-of-sub-account-trading-permissions" class="toc-h2 toc-link" data-title="Set a Batch of Sub-Account Trading Permissions">Set a Batch of Sub-Account Trading Permissions</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-assets-information-of-all-sub-accounts-under-the-master-account" class="toc-h2 toc-link" data-title="Query assets information of all sub-accounts under the master account">Query assets information of all sub-accounts under the master account</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-a-batch-of-sub-account-39-s-assets-information" class="toc-h2 toc-link" data-title="Query a Batch of Sub-Account&#39;s Assets Information">Query a Batch of Sub-Account's Assets Information</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-a-single-sub-account-39-s-assets-information" class="toc-h2 toc-link" data-title="Query a single sub-account&#39;s assets information">Query a single sub-account's assets information</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-a-single-sub-account-39-s-position-information" class="toc-h2 toc-link" data-title="Query a single sub-account&#39;s position information">Query a single sub-account's position information</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-account-financial-records" class="toc-h2 toc-link" data-title="Query account financial records">Query account financial records</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-financial-records-via-multiple-fields" class="toc-h2 toc-link" data-title="Query financial records via multiple fields">Query financial records via multiple fields</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-user-s-settlement-records" class="toc-h2 toc-link" data-title="Query user’s settlement records">Query user’s settlement records</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-user-s-available-leverage" class="toc-h2 toc-link" data-title="Query user’s available leverage">Query user’s available leverage</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-swap-information-on-order-limit" class="toc-h2 toc-link" data-title="Query swap information on order limit">Query swap information on order limit</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-information-on-swap-trading-fee" class="toc-h2 toc-link" data-title="Query information on swap trading fee">Query information on swap trading fee</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-information-on-transfer-limit" class="toc-h2 toc-link" data-title="Query information on Transfer Limit">Query information on Transfer Limit</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-information-on-position-limit" class="toc-h2 toc-link" data-title="Query information on position limit">Query information on position limit</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#transfer-between-master-and-sub-account" class="toc-h2 toc-link" data-title="Transfer between master and sub account">Transfer between master and sub account</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-transfer-records-between-master-and-sub-account" class="toc-h2 toc-link" data-title="Query transfer records between master and sub account">Query transfer records between master and sub account</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-user-39-s-api-indicator-disable-information" class="toc-h2 toc-link" data-title="Query user&#39;s API indicator disable information">Query user's API indicator disable information</a>
                  </li>
              </ul>
          </li>
          <li>
            <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#swap-trade-interface" class="toc-h1 toc-link" data-title="Swap Trade Interface">Swap Trade Interface</a>
              <ul class="toc-list-h2">
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#place-an-order" class="toc-h2 toc-link" data-title="Place an Order">Place an Order</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#place-a-batch-of-orders" class="toc-h2 toc-link" data-title="Place a Batch of Orders">Place a Batch of Orders</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#cancel-an-order" class="toc-h2 toc-link" data-title="Cancel an Order">Cancel an Order</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#cancel-all-orders" class="toc-h2 toc-link" data-title="Cancel All Orders">Cancel All Orders</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#place-lightning-close-order" class="toc-h2 toc-link" data-title="Place Lightning Close Order">Place Lightning Close Order</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#switch-leverage" class="toc-h2 toc-link" data-title="Switch Leverage">Switch Leverage</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#get-information-of-an-order" class="toc-h2 toc-link" data-title="Get Information of an Order">Get Information of an Order</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#order-details-acquisition" class="toc-h2 toc-link" data-title="Order details acquisition">Order details acquisition</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#current-unfilled-order-acquisition" class="toc-h2 toc-link" data-title="Current unfilled order acquisition">Current unfilled order acquisition</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#get-history-orders" class="toc-h2 toc-link" data-title="Get History Orders">Get History Orders</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-history-orders-via-multiple-fields" class="toc-h2 toc-link" data-title="Query history orders via multiple fields">Query history orders via multiple fields</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#acquire-history-match-results" class="toc-h2 toc-link" data-title="Acquire History Match Results">Acquire History Match Results</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-history-transactions-via-multiple-fields" class="toc-h2 toc-link" data-title="Query history transactions via multiple fields">Query history transactions via multiple fields</a>
                  </li>
              </ul>
          </li>
          <li>
            <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#swap-strategy-order-interface" class="toc-h1 toc-link" data-title="Swap Strategy Order Interface">Swap Strategy Order Interface</a>
              <ul class="toc-list-h2">
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#place-trigger-order" class="toc-h2 toc-link" data-title="Place Trigger Order">Place Trigger Order</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#cancel-trigger-order" class="toc-h2 toc-link" data-title="Cancel Trigger Order">Cancel Trigger Order</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#cancel-all-trigger-orders" class="toc-h2 toc-link" data-title="Cancel All Trigger Orders">Cancel All Trigger Orders</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-trigger-order-open-orders" class="toc-h2 toc-link" data-title="Query Trigger Order Open Orders">Query Trigger Order Open Orders</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-trigger-order-history" class="toc-h2 toc-link" data-title="Query Trigger Order History">Query Trigger Order History</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#set-a-take-profit-and-stop-loss-order-for-an-existing-position" class="toc-h2 toc-link" data-title="Set a Take-profit and Stop-loss Order for an Existing Position">Set a Take-profit and Stop-loss Order for an Existing Position</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#cancel-a-take-profit-and-stop-loss-order" class="toc-h2 toc-link" data-title="Cancel a Take-profit and Stop-loss Order">Cancel a Take-profit and Stop-loss Order</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#cancel-all-take-profit-and-stop-loss-orders" class="toc-h2 toc-link" data-title="Cancel all Take-profit and Stop-loss Orders">Cancel all Take-profit and Stop-loss Orders</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-open-take-profit-and-stop-loss-orders" class="toc-h2 toc-link" data-title="Query Open Take-profit and Stop-loss Orders">Query Open Take-profit and Stop-loss Orders</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-take-profit-and-stop-loss-history-orders" class="toc-h2 toc-link" data-title="Query Take-profit and Stop-loss History Orders">Query Take-profit and Stop-loss History Orders</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#query-info-of-take-profit-and-stop-loss-order-that-related-to-position-opening-order" class="toc-h2 toc-link" data-title="Query Info Of Take-profit and Stop-loss Order That Related To Position Opening Order">Query Info Of Take-profit and Stop-loss Order That Related To Position Opening Order</a>
                  </li>
              </ul>
          </li>
          <li>
            <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#swap-transferring-interface" class="toc-h1 toc-link" data-title="Swap Transferring Interface">Swap Transferring Interface</a>
              <ul class="toc-list-h2">
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#transfer-margin-between-spot-account-and-coin-margined-swap-account" class="toc-h2 toc-link" data-title="Transfer margin between Spot account and Coin Margined Swap account">Transfer margin between Spot account and Coin Margined Swap account</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#response-code-table" class="toc-h2 toc-link" data-title="Response Code Table">Response Code Table</a>
                  </li>
              </ul>
          </li>
          <li>
            <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#swap-websocket-reference" class="toc-h1 toc-link" data-title="Swap WebSocket Reference">Swap WebSocket Reference</a>
              <ul class="toc-list-h2">
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#api-list-2" class="toc-h2 toc-link" data-title="API List">API List</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#websocket-subscription-address" class="toc-h2 toc-link" data-title="WebSocket Subscription Address">WebSocket Subscription Address</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#api-rate-limit-illustration-2" class="toc-h2 toc-link" data-title="API Rate Limit Illustration">API Rate Limit Illustration</a>
                  </li>
              </ul>
          </li>
          <li>
            <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#websocket-heartbeat-and-authentication-interface" class="toc-h1 toc-link" data-title="WebSocket Heartbeat and Authentication Interface">WebSocket Heartbeat and Authentication Interface</a>
              <ul class="toc-list-h2">
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#market-heartbeat" class="toc-h2 toc-link" data-title="Market Heartbeat">Market Heartbeat</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#order-push-heartbeat" class="toc-h2 toc-link" data-title="Order Push Heartbeat">Order Push Heartbeat</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#order-push-address" class="toc-h2 toc-link" data-title="Order Push Address">Order Push Address</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#server-voluntarily-disconnects-connection" class="toc-h2 toc-link" data-title="Server voluntarily disconnects connection">Server voluntarily disconnects connection</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#server-return-error-code-but-remain-connection" class="toc-h2 toc-link" data-title="Server return error code but remain connection">Server return error code but remain connection</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#authentication" class="toc-h2 toc-link" data-title="Authentication">Authentication</a>
                  </li>
              </ul>
          </li>
          <li>
            <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#websocket-market-interface" class="toc-h1 toc-link" data-title="WebSocket Market Interface">WebSocket Market Interface</a>
              <ul class="toc-list-h2">
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#subscribe-kline-data" class="toc-h2 toc-link" data-title="Subscribe Kline data">Subscribe Kline data</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#request-kline-data" class="toc-h2 toc-link" data-title="Request Kline data">Request Kline data</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#subscribe-market-depth-data" class="toc-h2 toc-link" data-title="Subscribe Market Depth Data">Subscribe Market Depth Data</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#subscribe-incremental-market-depth-data" class="toc-h2 toc-link" data-title="Subscribe Incremental Market Depth Data">Subscribe Incremental Market Depth Data</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#subscribe-market-detail-data" class="toc-h2 toc-link" data-title="Subscribe Market Detail Data">Subscribe Market Detail Data</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#subscribe-market-bbo-data-push" class="toc-h2 toc-link" data-title="Subscribe market BBO data push">Subscribe market BBO data push</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#request-trade-detail-data" class="toc-h2 toc-link" data-title="Request Trade Detail Data">Request Trade Detail Data</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#subscribe-trade-detail-data" class="toc-h2 toc-link" data-title="Subscribe Trade Detail Data">Subscribe Trade Detail Data</a>
                  </li>
              </ul>
          </li>
          <li>
            <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#websocket-index-and-basis-interface" class="toc-h1 toc-link" data-title="WebSocket Index and Basis Interface">WebSocket Index and Basis Interface</a>
              <ul class="toc-list-h2">
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#subscribe-index-kline-data" class="toc-h2 toc-link" data-title="Subscribe Index Kline Data">Subscribe Index Kline Data</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#request-index-kline-data" class="toc-h2 toc-link" data-title="Request Index Kline Data">Request Index Kline Data</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#subscribe-premium-index-kline-data" class="toc-h2 toc-link" data-title="Subscribe Premium Index Kline Data">Subscribe Premium Index Kline Data</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#request-premium-index-kline-data" class="toc-h2 toc-link" data-title="Request Premium Index Kline Data">Request Premium Index Kline Data</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#subscribe-estimated-funding-rate-kline-data" class="toc-h2 toc-link" data-title="Subscribe Estimated Funding Rate Kline Data">Subscribe Estimated Funding Rate Kline Data</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#request-estimated-funding-rate-kline-data" class="toc-h2 toc-link" data-title="Request Estimated Funding Rate Kline Data">Request Estimated Funding Rate Kline Data</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#subscribe-basis-data" class="toc-h2 toc-link" data-title="Subscribe Basis Data">Subscribe Basis Data</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#request-basis-data" class="toc-h2 toc-link" data-title="Request Basis Data">Request Basis Data</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#subscribe-kline-data-of-mark-price" class="toc-h2 toc-link" data-title="Subscribe Kline Data of Mark Price">Subscribe Kline Data of Mark Price</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#request-kline-data-of-mark-price" class="toc-h2 toc-link" data-title="Request Kline Data of Mark Price">Request Kline Data of Mark Price</a>
                  </li>
              </ul>
          </li>
          <li>
            <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#orders-and-accounts-websocket-interfaces" class="toc-h1 toc-link" data-title="Orders and Accounts WebSocket Interfaces">Orders and Accounts WebSocket Interfaces</a>
              <ul class="toc-list-h2">
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#subscribe-order-data-sub" class="toc-h2 toc-link" data-title="Subscribe Order Data(sub)">Subscribe Order Data(sub)</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#unsubscribe-order-data-unsub" class="toc-h2 toc-link" data-title="Unsubscribe Order Data（unsub）">Unsubscribe Order Data（unsub）</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#subscribe-match-order-data-sub" class="toc-h2 toc-link" data-title="Subscribe Match Order Data（sub)">Subscribe Match Order Data（sub)</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#unsubscribe-match-order-data-unsub" class="toc-h2 toc-link" data-title="Unsubscribe Match Order Data（unsub）">Unsubscribe Match Order Data（unsub）</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#subscribe-account-equity-updates-data-sub" class="toc-h2 toc-link" data-title="Subscribe Account Equity Updates Data(sub)">Subscribe Account Equity Updates Data(sub)</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#unsubscribe-account-equity-updates-data-ubsub" class="toc-h2 toc-link" data-title="Unsubscribe Account Equity Updates Data (ubsub)">Unsubscribe Account Equity Updates Data (ubsub)</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#subscribe-position-updates-sub" class="toc-h2 toc-link" data-title="Subscribe Position Updates(sub)">Subscribe Position Updates(sub)</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#unsubscribe-position-updates-data-unsub" class="toc-h2 toc-link" data-title="Unsubscribe Position Updates Data(unsub)">Unsubscribe Position Updates Data(unsub)</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#subscribe-liquidation-orders-no-authentication-sub" class="toc-h2 toc-link" data-title="Subscribe Liquidation Orders (no authentication) (sub)">Subscribe Liquidation Orders (no authentication) (sub)</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#unsubscribe-liquidation-order-data-unsub" class="toc-h2 toc-link" data-title="Unsubscribe Liquidation Order Data (unsub)">Unsubscribe Liquidation Order Data (unsub)</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#subscribe-funding-rate-no-authentication-sub" class="toc-h2 toc-link" data-title="Subscribe funding rate (no authentication)（sub）">Subscribe funding rate (no authentication)（sub）</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#unsubscribe-funding-rate-data-no-authentication-unsub" class="toc-h2 toc-link" data-title="Unsubscribe Funding Rate Data(no authentication)(unsub)">Unsubscribe Funding Rate Data(no authentication)(unsub)</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#subscribe-contract-info-no-authentication-sub" class="toc-h2 toc-link" data-title="Subscribe Contract Info (no authentication)（sub）">Subscribe Contract Info (no authentication)（sub）</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#unsubscribe-contract-info-data-no-authentication-unsub" class="toc-h2 toc-link" data-title="Unsubscribe Contract Info Data(no authentication)(unsub)">Unsubscribe Contract Info Data(no authentication)(unsub)</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#subscribe-trigger-orders-updates-sub" class="toc-h2 toc-link" data-title="Subscribe trigger orders updates(sub)">Subscribe trigger orders updates(sub)</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#unsubscribe-trigger-orders-updates-unsub" class="toc-h2 toc-link" data-title="Unsubscribe trigger orders updates（unsub）">Unsubscribe trigger orders updates（unsub）</a>
                  </li>
              </ul>
          </li>
          <li>
            <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#websocket-interface-for-system-status-updates" class="toc-h1 toc-link" data-title="WebSocket interface for system status updates">WebSocket interface for system status updates</a>
              <ul class="toc-list-h2">
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#subscribe-system-status-updates" class="toc-h2 toc-link" data-title="Subscribe system status updates">Subscribe system status updates</a>
                  </li>
              </ul>
          </li>
          <li>
            <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#appendix" class="toc-h1 toc-link" data-title="Appendix">Appendix</a>
              <ul class="toc-list-h2">
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#operator-type-op" class="toc-h2 toc-link" data-title="Operator Type(OP)">Operator Type(OP)</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#topic-type" class="toc-h2 toc-link" data-title="Topic Type">Topic Type</a>
                  </li>
                  <li>
                    <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#response-code-err-code" class="toc-h2 toc-link" data-title="Response code（Err-Code）">Response code（Err-Code）</a>
                  </li>
              </ul>
          </li>
      </ul>
        <ul class="toc-footer">
            <li><a href="https://www.huobi.pro/apikey/">Sign Up for a Huobi API key </a></li>
            <li>Login is required for creating an API key</li>
        </ul>
    </div>
    <div class="page-wrapper">
      <div class="dark-box"></div>
      <div class="content">
        <h1 id="introduction">Introduction</h1><h2 id="api-documentation-summary">API Documentation Summary</h2>
<p>Welcome to the Huobi Coin Margined Swap API! You can use our API to access all market data, trading, and account management endpoints.</p>

<p>We have code examples in Shell! You can view code examples in the dark area to the right.</p>
<h2 id="market-maker-program">Market Maker Program</h2>
<p>Market maker program gives clients with good market making strategy an opportunity to have customized trading fee structure.</p>

<aside class="notice">
Market makers will not be able to use point cards, VIP rate, rebate or any other fee promotions.
</aside>
<h3 id="eligibility-criteria-as-a-market-maker-on-huobi-futures">Eligibility Criteria as a Market Maker on Huobi Futures</h3>
<p>Welcome users, who are dedicated to maker strategy and have created large trading volume, to participate in Huobi Futures long-term Market Maker project.If you have more than 3 BTC in your Huobi future account, or more than 3 BTC in your Huobi coin margined swap account, or you have more than 3 BTC in your Huobi option account,or more than 100000 USDT in your Huobi USDT Margined swap account, please send the following information to dm_mm@huobi.com:</p>

<ol>
<li>Huobi UIDs (not linked to any rebate program in any accounts)</li>
<li>Provide screenshot of trading volume for the past 30 days or VIP/corporate status with other Exchanges</li>
</ol>
<h1 id="changelog">Changelog</h1><h2 id="1-1-6-2021-2-26-added-query-asset-valuation-interface-query-a-batch-of-funding-rate-interface-modified-query-swap-price-limitation-interface-support-users-not-to-fill-in-all-input-parameters-and-the-interface-returns-the-price-limit-data-of-all-available-contracts-modified-query-the-last-trade-of-a-contract-interface-support-users-not-to-fill-in-all-input-parameters-the-interface-returns-the-latest-transaction-data-of-all-available-contracts-and-in-that-case-the-return-parameter-quot-ch-quot-value-is-quot-market-trade-detail-quot-added-one-field-in-return-quot-tick-quot-parameter-quot-contract_code-quot">1.1.6 2021-2-26 【Added: Query Asset Valuation interface, Query a Batch of Funding Rate interface. Modified Query Swap Price Limitation interface(Support users not to fill in all input parameters, and the interface returns the price limit data of all available contracts). Modified Query The Last Trade of a Contract interface(Support users not to fill in all input parameters, the interface returns the latest transaction data of all available contracts; And in that case, the return parameter "ch" value is "market.*trade.detail". Added one field in return "tick" parameter: "contract_code")】</h2><h3 id="1-added-query-asset-valuation-interface">1. Added Query Asset Valuation interface</h3>
<ul>
<li>Interface Name: Query Asset Valuation</li>
<li>Interface Type: private</li>
<li>interface URL: /swap-api/v1/swap_balance_valuation</li>
</ul>
<h3 id="2-added-query-a-batch-of-funding-rate-interface">2. Added Query a Batch of Funding Rate interface</h3>
<ul>
<li>Interface Name: Query a Batch of Funding Rate</li>
<li>Interface Type: public</li>
<li>interface URL: /swap-api/v1/swap_batch_funding_rate</li>
</ul>
<h3 id="3-modified-query-swap-price-limitation-interface-support-users-not-to-fill-in-all-input-parameters-and-the-interface-returns-the-price-limit-data-of-all-available-contracts">3. Modified Query Swap Price Limitation interface(Support users not to fill in all input parameters, and the interface returns the price limit data of all available contracts)</h3>
<ul>
<li>Interface Name: Query Swap Price Limitation</li>
<li>Interface Type: public</li>
<li>interface URL: /swap-api/v1/swap_price_limit</li>
</ul>
<h3 id="4-modified-query-the-last-trade-of-a-contract-interface-support-users-not-to-fill-in-all-input-parameters-the-interface-returns-the-latest-transaction-data-of-all-available-contracts-and-in-that-case-the-return-parameter-quot-ch-quot-value-is-quot-market-trade-detail-quot-added-one-field-in-return-quot-data-quot-parameter-quot-contract_code-quot">4. Modified Query The Last Trade of a Contract interface(Support users not to fill in all input parameters, the interface returns the latest transaction data of all available contracts; And in that case, the return parameter "ch" value is "market.*trade.detail". Added one field in return "data" parameter: "contract_code")</h3>
<ul>
<li>Interface Name: Query The Last Trade of a Contract</li>
<li>Interface Type: public</li>
<li>interface URL: /swap-ex/market/trade</li>
</ul>
<h2 id="1-1-5-2021-2-5-added-query-information-on-tiered-margin-set-a-batch-of-sub-account-trading-permissions-query-a-batch-of-sub-account-39-s-assets-information-4-7-modified-the-existing-interfaces-and-added-new-parameters-8-query-user-s-settlement-records-interface-to-avoid-affecting-system-performance-the-interface-only-supports-querying-user-settlement-records-in-the-last-90-days">1.1.5 2021-2-5 【Added: Query information on Tiered Margin. Set a Batch of Sub-Account Trading Permissions. Query a Batch of Sub-Account's Assets Information. 4-7 Modified the existing interfaces and added new parameters. 8 Query user’s settlement records interface(To avoid affecting system performance, the interface only supports querying user settlement records in the last 90 days)】</h2><h3 id="1-added-query-information-on-tiered-margin-interface">1. Added Query information on Tiered Margin interface</h3>
<ul>
<li>Interface Name: Query information on Tiered Margin</li>
<li>Interface Type: public</li>
<li>Interface URL: /swap-api/v1/swap_ladder_margin</li>
</ul>
<h3 id="2-added-set-a-batch-of-sub-account-trading-permissions-interface">2. Added Set a Batch of Sub-Account Trading Permissions interface</h3>
<ul>
<li>Interface Name: Set a Batch of Sub-Account Trading Permissions</li>
<li>Interface Type: private</li>
<li>Interface URL: /swap-api/v1/swap_sub_auth</li>
</ul>
<h3 id="3-added-query-a-batch-of-sub-account-39-s-assets-information-interface">3. Added Query a Batch of Sub-Account's Assets Information interface</h3>
<ul>
<li>Interface Name: Query a Batch of Sub-Account's Assets Information</li>
<li>Interface Type: private</li>
<li>Interface URL: /swap-api/v1/swap_sub_account_info_list</li>
</ul>
<h3 id="4-modified-query-the-last-trade-of-a-contract-interface-added-quot-quantity-quot-in-return-parameter-quot-data-quot-which-means-the-trading-quantity-coin-calculation-formula-quantity-coin-trading-quantity-cont-contract-size-trade-price">4. Modified Query The Last Trade of a Contract interface(Added "quantity" in return parameter "data", which means the trading quantity(coin), Calculation formula: quantity(coin) = trading quantity(cont) * contract size/ trade price)</h3>
<ul>
<li>Interface Name: Query The Last Trade of a Contract</li>
<li>Interface Type: public</li>
<li>Interface URL: /swap-ex/market/trade</li>
</ul>
<h3 id="5-modified-query-a-batch-of-trade-records-of-a-contract-interface-added-quot-quantity-quot-in-return-parameter-quot-data-quot-which-means-the-trading-quantity-coin-calculation-formula-quantity-coin-trading-quantity-cont-contract-size-trade-price">5. Modified Query a Batch of Trade Records of a Contract interface（(Added "quantity" in return parameter "data", which means the trading quantity(coin), Calculation formula: quantity(coin) = trading quantity(cont) * contract size/ trade price)</h3>
<ul>
<li>Interface Name: Query a Batch of Trade Records of a Contract</li>
<li>Interface Type: public</li>
<li>Interface URL: /swap-ex/market/history/trade</li>
</ul>
<h3 id="6-modified-subscribe-trade-detail-data-interface-added-quot-quantity-quot-in-return-parameter-quot-data-quot-which-means-the-trading-quantity-coin-calculation-formula-quantity-coin-trading-quantity-cont-contract-size-trade-price">6. Modified Subscribe Trade Detail Data interface（(Added "quantity" in return parameter "data", which means the trading quantity(coin), Calculation formula: quantity(coin) = trading quantity(cont) * contract size/ trade price)</h3>
<ul>
<li>Interface Name: Subscribe Trade Detail Data</li>
<li>Interface Type: public</li>
<li>Subscription Topic: market.$contract_code.trade.detail</li>
</ul>
<h3 id="7-modified-request-trade-detail-data-interface-added-quot-quantity-quot-in-return-parameter-quot-data-quot-which-means-the-trading-quantity-coin-calculation-formula-quantity-coin-trading-quantity-cont-contract-size-trade-price">7. Modified Request Trade Detail Data interface(Added "quantity" in return parameter "data", which means the trading quantity(coin), Calculation formula: quantity(coin) = trading quantity(cont) * contract size/ trade price)</h3>
<ul>
<li>Interface Name: Request Trade Detail Data</li>
<li>Interface Type: public</li>
<li>Subscription Topic: market.$contract_code.trade.detail</li>
</ul>
<h3 id="8-modified-query-user-s-settlement-records-interface-to-avoid-affecting-system-performance-the-interface-only-supports-querying-user-settlement-records-in-the-last-90-days">8. Modified Query user’s settlement records interface(To avoid affecting system performance, the interface only supports querying user settlement records in the last 90 days)</h3>
<ul>
<li>Interface Name: Query user’s settlement records</li>
<li>Interface Type: private</li>
<li>Interface URL: /swap-api/v1/swap_user_settlement_records</li>
</ul>
<h2 id="1-1-4-2021-1-29-added-get-a-batch-of-market-data-overview-get-kline-data-of-mark-price-subscribe-kline-data-of-mark-price-request-kline-data-of-mark-price-5-17-added-fields-to-modify-interface-the-order_id-of-submitted-trigger-order-response-has-been-changed-from-the-original-natural-number-self-incrementing-id-to-a-unique-identification-id-with-a-length-of-18-digits-it-is-recommended-to-use-the-order_id_str-order_id-in-string-type-of-submitted-order-response-to-avoid-the-occurrence-of-truncation-by-the-system-because-excessive-length">1.1.4 2021-1-29 【Added:Get a Batch of Market Data Overview、Get Kline Data of Mark Price、Subscribe Kline Data of Mark Price、Request Kline Data of Mark Price. 5-17 Added fields to modify interface. The order_id of submitted trigger order response has been changed from the original natural number self-incrementing ID to a unique identification ID with a length of 18 digits. It is recommended to use the order_id_str (order_id in string type) of submitted order response  to avoid the occurrence of truncation by the system because excessive length.】</h2><h3 id="1-added-get-a-batch-of-market-data-overview">1. Added Get a Batch of Market Data Overview</h3>
<ul>
<li>Interface Name: Get a Batch of Market Data Overview</li>
<li>Interface Type: public</li>
<li>Interface URL: /swap-ex/market/detail/batch_merged</li>
</ul>
<h3 id="2-added-get-kline-data-of-mark-price">2. Added Get Kline Data of Mark Price</h3>
<ul>
<li>Interface Name: Get Kline Data of Mark Price</li>
<li>Interface Type: public</li>
<li>Interface URL: /index/market/history/swap_mark_price_kline</li>
</ul>
<h3 id="3-added-subscribe-kline-data-of-mark-price">3. Added Subscribe Kline Data of Mark Price</h3>
<ul>
<li>Interface Name: Subscribe Kline Data of Mark Price</li>
<li>Interface Type: public</li>
<li>Subscription topic: market.$contract_code.mark_price.$period</li>
</ul>
<h3 id="4-added-request-kline-data-of-mark-price">4. Added Request Kline Data of Mark Price</h3>
<ul>
<li>Interface Name: Request Kline Data of Mark Price</li>
<li>Interface Type: public</li>
<li>Subscription topic: market.$contract_code.mark_price.$period</li>
</ul>
<h3 id="5-modified-cancel-all-orders-added-two-optional-parameters-in-request-direction-indicates-order-direction-if-not-filled-in-means-both-with-available-values-buy-sell-offset-order-offset-if-not-filled-in-means-both-with-available-values-open-close">5. Modified Cancel All Orders(Added two optional parameters in request: direction, indicates order direction, if not filled in means both with available values: “buy”, “sell”. offset, order offset, if not filled in means both with available values: “open”, “close”.)</h3>
<ul>
<li>Interface Name: Cancel All Orders</li>
<li>Interface Type: private</li>
<li>Interface URL: /swap-api/v1/swap_cancelall</li>
</ul>
<h3 id="6-modified-get-information-of-an-order-added-one-field-in-return-parameter-quot-data-quot-real_profit-real-profit-when-close-position">6. Modified Get Information of an Order(Added one field in return parameter "data": real_profit(real profit when close position).)</h3>
<ul>
<li>Interface Name: Get Information of an Order</li>
<li>Interface Type: private</li>
<li>Interface URL: /swap-api/v1/swap_order_info</li>
</ul>
<h3 id="7-modified-order-details-acquisition-added-field-in-return-parameters-both-quot-data-quot-and-quot-trades-quot-real_profit-real-profit-when-close-position-and-added-one-filed-in-quot-trades-quot-to-indicates-each-trade-profit-profit-profit-when-close-position">7. Modified Order details acquisition(Added field in return parameters both "data" and "trades": real_profit(real profit when close position). And added one filed in "trades" to indicates each trade profit：profit(profit when close position))</h3>
<ul>
<li>Interface Name: Order details acquisition</li>
<li>Interface Type: private</li>
<li>Interface URL: /swap-api/v1/swap_order_detail</li>
</ul>
<h3 id="8-modified-current-unfilled-order-acquisition-added-two-optional-parameters-in-request-sort_by-is-sort-field-if-not-filled-in-means-order-by-create_at-descending-with-available-values-created_at-descending-order-update_time-descending-order-trade_type-indicates-trade-type-if-not-filled-in-means-all-with-available-values-0-all-1-open-long-2-open-short-3-close-short-4-close-long-added-two-fields-in-return-parameter-quot-orders-quot-update_time-order-updated-time-in-milliseconds-real_profit-real-profit-when-close-position">8. Modified Current unfilled order acquisition(Added two optional parameters in request: sort_by, is sort field, if not filled in means order by create_at descending, with available values “created_at”(descending order), “update_time”(descending order); trade_type, indicates trade type, if not filled in means all, with available values: 0:all, 1:open long, 2:open short, 3:close short, 4:close long. Added two fields in return parameter "orders": update_time(order updated time, in milliseconds), real_profit(real profit when close position).)</h3>
<ul>
<li>Interface Name: Current unfilled order acquisition</li>
<li>Interface Type: private</li>
<li>Interface URL: /swap-api/v1/swap_openorders</li>
</ul>
<h3 id="9-modified-get-history-orders-added-one-field-in-return-parameter-quot-orders-quot-real_profit-real-profit-when-close-position">9. Modified Get History Orders(Added one field in return parameter "orders": real_profit(real profit when close position).)</h3>
<ul>
<li>Interface Name: Get History Orders</li>
<li>Interface Type: private</li>
<li>Interface URL: /swap-api/v1/swap_hisorders</li>
</ul>
<h3 id="10-modified-query-history-orders-via-multiple-fields-added-one-field-in-return-parameter-quot-orders-quot-real_profit-real-profit-when-close-position">10. Modified Query history orders via multiple fields(Added one field in return parameter "orders": real_profit(real profit when close position).)</h3>
<ul>
<li>Interface Name: Query history orders via multiple fields</li>
<li>Interface Type: private</li>
<li>Interface URL: /swap-api/v1/swap_hisorders_exact</li>
</ul>
<h3 id="11-modified-acquire-history-match-results-added-one-field-in-return-parameter-quot-trades-quot-real_profit-real-profit-when-close-position">11. Modified Acquire History Match Results(Added one field in return parameter "trades": real_profit(real profit when close position).)</h3>
<ul>
<li>Interface Name: Acquire History Match Results</li>
<li>Interface Type: private</li>
<li>Interface URL: /swap-api/v1/swap_matchresults</li>
</ul>
<h3 id="12-modified-query-history-transactions-via-multiple-fields-added-one-field-in-return-parameter-quot-trades-quot-real_profit-real-profit-when-close-position">12. Modified Query history transactions via multiple fields(Added one field in return parameter "trades": real_profit(real profit when close position).)</h3>
<ul>
<li>Interface Name: Query history transactions via multiple fields</li>
<li>Interface Type: private</li>
<li>Interface URL: /swap-api/v1/swap_matchresults_exact</li>
</ul>
<h3 id="13-modified-subscribe-order-data-sub-added-one-field-in-return-data-real_profit-real-profit-when-close-position-added-two-fields-in-return-parameter-quot-trade-quot-profit-profit-when-close-position-real_profit-real-profit-when-close-position">13. Modified Subscribe Order Data(sub)(Added one field in return data: real_profit(real profit when close position).added two fields in return parameter "trade": profit(profit when close position),  real_profit(real profit when close position))</h3>
<ul>
<li>Interface Name: Subscribe Order Data(sub)</li>
<li>Interface Type: private</li>
<li>Subscription topic: orders.$contract_code</li>
</ul>
<h3 id="14-modified-cancel-all-trigger-orders-added-two-optional-parameters-in-request-direction-order-direction-if-not-filled-in-means-both-with-available-valuse-buy-sell-offset-order-offset-if-not-filled-in-means-both-with-available-values-open-close">14. Modified Cancel All Trigger Orders(Added two optional parameters in request: direction, order direction, if not filled in means both, with available valuse: “buy”, “sell”; offset, order offset, if not filled in means both with available values: “open”, “close”.)</h3>
<ul>
<li>Interface Name: Cancel All Trigger Orders</li>
<li>Interface Type: private</li>
<li>Interface URL: /swap-api/v1/swap_trigger_cancelall</li>
</ul>
<h3 id="15-modified-cancel-all-take-profit-and-stop-loss-orders-added-one-parameter-in-request-direction-order-direction-if-not-filled-in-means-both-with-available-valuse-buy-sell">15. Modified Cancel all Take-profit and Stop-loss Orders(Added one parameter in request: direction, order direction, if not filled in means both, with available valuse: “buy”, “sell”.)</h3>
<ul>
<li>Interface Name: Cancel all Take-profit and Stop-loss Orders</li>
<li>Interface Type: private</li>
<li>Interface URL: /swap-api/v1/swap_tpsl_cancelall</li>
</ul>
<h3 id="16-modified-query-trigger-order-open-orders-added-one-parameter-in-request-trade_type-order-trade-type-if-not-filled-in-means-all-with-available-values-0-all-1-open-long-2-open-short-3-close-short-4-close-long">16. Modified Query Trigger Order Open Orders(Added one parameter in request: trade_type, order trade type, if not filled in means all with available values 0:all, 1:open long, 2:open short, 3:close short, 4:close long.)</h3>
<ul>
<li>Interface Name: Query Trigger Order Open Orders</li>
<li>Interface Type: private</li>
<li>Interface URL: /swap-api/v1/swap_trigger_openorders</li>
</ul>
<h3 id="17-modified-query-open-take-profit-and-stop-loss-orders-added-one-parameter-in-request-trade_type-order-trade-type-if-not-filled-in-means-all-with-available-values-0-all-3-close-short-4-close-long">17. Modified Query Open Take-profit and Stop-loss Orders(Added one parameter in request: trade_type, order trade type, if not filled in means all with available values 0:all, 3:close short, 4:close long.)</h3>
<ul>
<li>Interface Name: Query Open Take-profit and Stop-loss Orders</li>
<li>Interface Type: private</li>
<li>Interface URL: /swap-api/v1/swap_tpsl_openorders</li>
</ul>
<h2 id="1-1-3-2021-01-12-1-added-get-the-estimated-settlement-price-2-7-added-set-a-take-profit-and-stop-loss-order-interfaces-8-21-added-fields-to-modify-interface-added-the-first-level-menu-of-contract-trigger-order-and-add-take-profit-and-stop-loss-related-interfaces-and-move-the-original-contract-trigger-order-related-interfaces-to-this-menu">1.1.3 2021-01-12 【1 Added Get the estimated settlement price. 2-7 Added ”Set a Take-profit and Stop-loss Order“ interfaces. 8-21 Added fields to modify interface. Added the first-level menu of [Contract Trigger Order], and add take-profit and stop-loss related interfaces and move the original contract trigger order related interfaces to this menu 】</h2><h3 id="1-added-get-the-estimated-settlement-price">1. Added Get the estimated settlement price</h3>
<ul>
<li>Interface Name: Get the estimated settlement price</li>
<li>Interface Type: public</li>
<li>Interface URL: /swap-api/v1/swap_estimated_settlement_price</li>
</ul>
<h3 id="2-added-set-a-take-profit-and-stop-loss-order-for-an-existing-position">2. Added Set a Take-profit and Stop-loss Order for an Existing Position</h3>
<ul>
<li>Interface Name: Set a Take-profit and Stop-loss Order for an Existing Position</li>
<li>Interface Type: private</li>
<li>Interface URL: /swap-api/v1/swap_tpsl_order</li>
</ul>
<h3 id="3-added-cancel-a-take-profit-and-stop-loss-order">3. Added Cancel a Take-profit and Stop-loss Order</h3>
<ul>
<li>Interface Name: Cancel a Take-profit and Stop-loss Order</li>
<li>Interface Type: private</li>
<li>Interface URL: /swap-api/v1/swap_tpsl_cancel</li>
</ul>
<h3 id="4-added-cancel-all-take-profit-and-stop-loss-orders">4. Added Cancel all Take-profit and Stop-loss Orders</h3>
<ul>
<li>Interface Name: Cancel all Take-profit and Stop-loss Orders</li>
<li>Interface Type: private</li>
<li>Interface URL: /swap-api/v1/swap_tpsl_cancelall</li>
</ul>
<h3 id="5-added-query-open-take-profit-and-stop-loss-orders">5. Added Query Open Take-profit and Stop-loss Orders</h3>
<ul>
<li>Interface Name: Query Open Take-profit and Stop-loss Orders </li>
<li>Interface Type: private</li>
<li>Interface URL: /swap-api/v1/swap_tpsl_openorders</li>
</ul>
<h3 id="6-added-query-take-profit-and-stop-loss-history-orders">6. Added Query Take-profit and Stop-loss History Orders</h3>
<ul>
<li>Interface Name: Query Take-profit and Stop-loss History Orders</li>
<li>Interface Type: private</li>
<li>Interface URL: /swap-api/v1/swap_tpsl_hisorders</li>
</ul>
<h3 id="7-added-query-info-of-take-profit-and-stop-loss-order-that-related-to-position-opening-order">7. Added Query Info Of Take-profit and Stop-loss Order That Related To Position Opening Order</h3>
<ul>
<li>Interface Name:  Query Info Of Take-profit and Stop-loss Order That Related To Position Opening Order</li>
<li>Interface Type: private</li>
<li>Interface URL: /swap-api/v1/swap_relation_tpsl_order</li>
</ul>
<h3 id="8-modifed-quot-place-an-order-quot-interface-added-optional-parameters-tp_trigger_price-trigger-price-of-take-profit-order-tp_order_price-order-price-of-take-profit-order-tp_order_price_type-order-type-of-take-profit-order-sl_trigger_price-trigger-price-of-stop-loss-order-sl_order_price-order-price-of-stop-loss-order-sl_order_price_type-order-type-of-stop-loss-order">8. Modifed "Place an order" Interface（added optional parameters: tp_trigger_price (Trigger price of take-profit order), tp_order_price (Order price of take-profit order), tp_order_price_type (Order type of take-profit order), sl_trigger_price (Trigger price of stop-loss order), sl_order_price (Order price of stop-loss order), sl_order_price_type (Order type of stop-loss order)）</h3>
<ul>
<li>Interface Name: Place an Order</li>
<li>Interface Type: private</li>
<li>Interface URL: /swap-api/v1/swap_order</li>
</ul>
<h3 id="9-modified-quot-place-a-batch-of-orders-quot-interface-added-optional-parameters-in-parameters-quot-orders_data-quot-tp_trigger_price-trigger-price-of-take-profit-order-tp_order_price-order-price-of-take-profit-order-tp_order_price_typeorder-type-of-take-profit-order-sl_trigger_price-trigger-price-of-stop-loss-order-sl_order_price-order-price-of-stop-loss-order-sl_order_price_type-order-type-of-stop-loss-order">9. Modified "Place a batch of orders" Interface (added optional parameters in parameters "orders_data": tp_trigger_price (Trigger price of take-profit order)，tp_order_price (Order price of take-profit order), tp_order_price_typeOrder type of take-profit order), sl_trigger_price (Trigger price of stop-loss order), sl_order_price (Order price of stop-loss order), sl_order_price_type (Order type of stop-loss order)）</h3>
<ul>
<li>Interface Name: Place a Batch of Orders</li>
<li>Interface Type: private</li>
<li>Interface URL: /swap-api/v1/swap_batchorder</li>
</ul>
<h3 id="10-modified-quot-get-information-of-an-order-quot-interface-added-return-parameter-quot-is_tpsl-quot-to-indicate-whether-to-set-take-profit-and-stop-loss-order-1-yes-0-no-added-quot-enumerated-values-quot-in-return-parameter-quot-order_source-quot-tpsl-indicates-triggered-by-take-profit-and-stop-loss">10. Modified "Get Information of an Order" Interface（Added return parameter "is_tpsl" to indicate whether to set take-profit and stop-loss order, 1: yes, 0: no); added "enumerated values" in return parameter "order_source"（“tpsl” indicates triggered by take-profit and stop-loss））</h3>
<ul>
<li>Interface Name: Get Information of an Order</li>
<li>Interface Type: private</li>
<li>Interface URL: /swap-api/v1/swap_order_info</li>
</ul>
<h3 id="11-modified-quot-order-details-acquisition-quot-interface-added-return-parameter-quot-is_tpsl-quot-to-indicate-whether-to-set-take-profit-and-stop-loss-order-1-yes-0-no-added-quot-enumerated-values-quot-in-return-parameter-quot-order_source-quot-tpsl-indicates-triggered-by-take-profit-and-stop-loss">11. Modified "Order details acquisition" Interface（Added return parameter "is_tpsl" to indicate whether to set take-profit and stop-loss order, 1: yes, 0: no); added "enumerated values" in return parameter "order_source"（“tpsl” indicates triggered by take-profit and stop-loss））</h3>
<ul>
<li>Interface Name: Order details acquisition<br></li>
<li>Interface Type: private</li>
<li>Interface URL: /swap-api/v1/swap_order_detail</li>
</ul>
<h3 id="12-modified-quot-current-unfilled-order-acquisition-quot-interface-added-return-parameter-quot-is_tpsl-quot-to-indicate-whether-to-set-take-profit-and-stop-loss-order-1-yes-0-no-added-quot-enumerated-values-quot-in-return-parameter-quot-order_source-quot-tpsl-indicates-triggered-by-take-profit-and-stop-loss">12. Modified "Current unfilled order acquisition" Interface（Added return parameter "is_tpsl" to indicate whether to set take-profit and stop-loss order, 1: yes, 0: no); added "enumerated values"in return parameter "order_source"（“tpsl” indicates triggered by take-profit and stop-loss））</h3>
<ul>
<li>Interface Name: Current unfilled order acquisition</li>
<li>Interface Type: private</li>
<li>Interface URL: /swap-api/v1/swap_openorders</li>
</ul>
<h3 id="13-modified-quot-get-history-orders-quot-interface-added-paprameter-quot-sort_by-quot-to-represent-quot-sort-fields-quot-with-optional-value-create_date-and-update_time-quot-added-return-parameter-quot-is_tpsl-quot-to-indicate-whether-to-set-take-profit-and-stop-loss-order-1-yes-0-no-and-quot-update_time-quot-to-indicate-order-39-s-update-time-and-quot-enumerated-values-quot-in-return-parameter-quot-order_source-quot-tpsl-indicates-triggered-by-take-profit-and-stop-loss">13. Modified "Get History Orders" Interface（Added paprameter "sort_by" to represent "sort fields" with optional value“create_date” and “update_time"; added return parameter "is_tpsl" to indicate whether to set take-profit and stop-loss order, 1: yes, 0: no), and "update_time" to indicate order's update time）; and "enumerated values" in return parameter "order_source"（“tpsl” indicates triggered by take-profit and stop-loss））</h3>
<ul>
<li>Interface Name: Get History Orders</li>
<li>Interface Type: private</li>
<li>Interface URL: /swap-api/v1/swap_hisorders</li>
</ul>
<h3 id="14-modified-quot-query-history-orders-via-multiple-fields-quot-interface-added-return-parameter-quot-is_tpsl-quot-to-indicate-whether-to-set-take-profit-and-stop-loss-order-1-yes-0-no-added-quot-enumerated-values-quot-in-return-parameter-quot-order_source-quot-tpsl-indicates-triggered-by-take-profit-and-stop-loss">14. Modified "Query history orders via multiple fields" Interface（Added return parameter "is_tpsl" to indicate whether to set take-profit and stop-loss order, 1: yes, 0: no); added "enumerated values"in return parameter "order_source"（“tpsl” indicates triggered by take-profit and stop-loss））</h3>
<ul>
<li>Interface Name: Query history orders via multiple fields</li>
<li>Interface Type: private</li>
<li>Interface URL: /swap-api/v1/swap_hisorders_exact</li>
</ul>
<h3 id="15-modified-quot-subscribe-order-data-sub-quot-interface-added-return-parameter-quot-is_tpsl-quot-to-indicate-whether-to-set-take-profit-and-stop-loss-order-1-yes-0-no-added-quot-enumerated-values-quot-in-return-parameter-quot-order_source-quot-tpsl-indicates-triggered-by-take-profit-and-stop-loss">15. Modified "Subscribe Order Data(sub)" Interface（Added return parameter "is_tpsl" to indicate whether to set take-profit and stop-loss order, 1: yes, 0: no); added "enumerated values"in return parameter "order_source"（“tpsl” indicates triggered by take-profit and stop-loss））</h3>
<ul>
<li>Interface Name: Subscribe Order Data(sub)</li>
<li>Interface Type: private</li>
<li>Subscription Topic: orders.$contract_code</li>
</ul>
<h3 id="16-modified-quot-subscribe-match-order-data-sub-quot-interface-added-return-parameter-quot-is_tpsl-quot-to-indicate-whether-to-set-take-profit-and-stop-loss-order-1-yes-0-no-added-quot-enumerated-values-quot-in-return-parameter-quot-order_source-quot-tpsl-indicates-triggered-by-take-profit-and-stop-loss">16. Modified "Subscribe Match Order Data（sub）" Interface（Added return parameter "is_tpsl" to indicate whether to set take-profit and stop-loss order, 1: yes, 0: no); added "enumerated values" in return parameter "order_source"（“tpsl” indicates triggered by take-profit and stop-loss））</h3>
<ul>
<li>Interface Name: Subscribe Match Order Data（sub)<br></li>
<li>Interface Type: private</li>
<li>Subscription Topic: matchOrders.$contract_code</li>
</ul>
<h3 id="17-modified-quot-query-trigger-order-history-quot-interface-added-paprameter-quot-sort_by-quot-to-represent-quot-sort-fields-quot-with-optional-values-created_at-and-update_time-added-quot-update_time-quot-to-indicate-order-39-s-update-time">17. Modified "Query Trigger Order History" Interface（Added paprameter "sort_by" to represent "sort fields" with optional values “created_at” and “update_time”). added "update_time" to indicate order's update time））</h3>
<ul>
<li>Interface Name: Query Trigger Order History<br></li>
<li>Interface Type: private</li>
<li>Interface URL: /swap-api/v1/swap_trigger_hisorders</li>
</ul>
<h3 id="18-modified-quot-get-swap-open-interest-information-quot-interface-added-quot-trade_volume-quot-in-return-parameter-quot-data-quot-to-indicate-trading-volume-within-the-last-24-hours-cont-and-quot-trade_amount-quot-to-indicate-trading-volume-within-the-last-24-hours-coin-and-quot-trade_turnover-quot-to-represent-trading-amount-within-the-last-24-hours">18. Modified "Get Swap Open Interest Information" Interface (Added "trade_volume" in return parameter "data" to indicate trading volume within the last 24 hours (cont),  and "trade_amount" to indicate trading volume within the last 24 hours (coin), and "trade_turnover" to represent trading amount within the last 24 hours.)</h3>
<ul>
<li>Interface Name: Get Swap Open Interest Information</li>
<li>Interface Type: public</li>
<li>Interface URL: /swap-api/v1/swap_open_interest</li>
</ul>
<h3 id="19-modified-quot-subscribe-market-detail-data-quot-interface-added-quot-ask-quot-in-return-parameter-tick-to-represent-sell-one-and-bid-to-represent-quot-buy-one-quot">19. Modified "Subscribe Market Detail Data" Interface (Added "ask" in return parameter “tick” to represent “sell one” and “bid” to represent "buy one".)</h3>
<ul>
<li>Interface Name: Subscribe Market Detail Data</li>
<li>Interface Type: public</li>
<li>Subscription Topic: market.$contract_code.detail</li>
</ul>
<h3 id="20-modified-quot-query-swap-info-quot-interface-added-quot-delivery_time-quot-in-return-parameter-to-represent-delivery-time-millesecond-timestamp">20. Modified "Query Swap Info" Interface（Added "delivery_time" in return parameter to represent delivery time（millesecond timestamp））</h3>
<ul>
<li>Interface Name: Query Swap Info</li>
<li>Interface Type: public</li>
<li>Interface URL: /swap-api/v1/swap_contract_info</li>
</ul>
<h3 id="21-modified-quot-subscribe-market-detail-data-quot-interface-added-quot-delivery_time-quot-in-return-parameter-to-represent-delivery-time-millesecond-timestamp">21. Modified "Subscribe Market Detail Data" Interface（Added "delivery_time" in return parameter to represent delivery time（millesecond timestamp））</h3>
<ul>
<li>Interface Name: Subscribe Contract Info (no authentication)（sub）</li>
<li>Interface Type: public</li>
<li>Subscription Topic: public.$contract_code.contract_info</li>
</ul>
<h2 id="1-1-2-2020-12-02-modified-order-details-acquisition-interface-when-querying-cancelation-data-of-orders-that-have-not-been-partially-filled-if-created_at-and-order_type-parameters-are-not-uploaded-the-data-that-can-be-queried-reduced-from-last-12-hours-to-last-2-hours-modified-query-history-orders-interface-when-querying-cancelation-data-of-orders-that-have-not-been-partially-filled-the-data-that-can-be-retained-reduced-from-last-24-hours-to-last-2-hours-modified-query-history-orders-via-multiple-fields-interface-when-querying-cancelation-data-of-orders-that-have-not-been-partially-filled-the-data-that-can-be-retained-reduced-from-last-24-hours-to-last-2-hours">1.1.2 2020-12-02 【Modified “Order details acquisition” interface (When querying cancelation data of orders that have not been partially filled, if “created_at” and “order_type” parameters are not uploaded, the data that can be queried reduced from last 12 hours to last 2 hours.); modified “Query history orders” interface (When querying cancelation data of orders that have not been partially filled, the data that can be retained reduced from last 24 hours to last 2 hours.); modified “Query history orders via multiple fields” interface (When querying cancelation data of orders that have not been partially filled, the data that can be retained reduced from last 24 hours to last 2 hours.)】</h2><h3 id="1-modified-order-details-acquisition-interface-when-querying-cancelation-data-of-orders-that-have-not-been-partially-filled-if-created_at-and-order_type-parameters-are-not-uploaded-the-data-that-can-be-queried-reduced-from-last-12-hours-to-last-2-hours">1、Modified “Order details acquisition” interface (When querying cancelation data of orders that have not been partially filled, if “created_at” and “order_type” parameters are not uploaded, the data that can be queried reduced from last 12 hours to last 2 hours.)</h3>
<ul>
<li><p>Interface Name：Order details acquisition</p></li>
<li><p>Interface Type：private</p></li>
<li><p>Interface URL：swap-api/v1/swap_order_detail</p></li>
</ul>
<h3 id="2-modified-query-history-orders-interface-when-querying-cancelation-data-of-orders-that-have-not-been-partially-filled-the-data-that-can-be-retained-reduced-from-last-24-hours-to-last-2-hours">2、modified “Query history orders” interface (When querying cancelation data of orders that have not been partially filled, the data that can be retained reduced from last 24 hours to last 2 hours.)</h3>
<ul>
<li><p>Interface Name：Get History Orders</p></li>
<li><p>Interface Type：private</p></li>
<li><p>Interface URL：swap-api/v1/swap_hisorders</p></li>
</ul>
<h3 id="3-modified-query-history-orders-via-multiple-fields-interface-when-querying-cancelation-data-of-orders-that-have-not-been-partially-filled-the-data-that-can-be-retained-reduced-from-last-24-hours-to-last-2-hours">3、modified “Query history orders via multiple fields” interface (When querying cancelation data of orders that have not been partially filled, the data that can be retained reduced from last 24 hours to last 2 hours.)</h3>
<ul>
<li><p>Interface Name：Query history orders via multiple fields</p></li>
<li><p>Interface Type：private</p></li>
<li><p>Interface URL：swap-api/v1/swap_hisorders_exact</p></li>
</ul>
<h2 id="1-1-1-2020-11-24-added-query-historical-settlement-records-of-the-platform-interface-modified-added-fields-of-return-parameter-for-quot-query-liquidation-orders-quot-interface-and-quot-subscribe-liquidation-order-data-quot-interface">1.1.1 2020-11-24 【Added: Query historical settlement records of the platform interface. Modified:  Added fields of return parameter for "Query Liquidation Orders" interface and "Subscribe Liquidation Order Data" interface】</h2><h3 id="1-added-query-historical-settlement-records-of-the-platform-interface">1、Added “Query historical settlement records of the platform” interface</h3>
<ul>
<li><p>Interface Name: Query historical settlement records of the platform</p></li>
<li><p>Interface Type: public</p></li>
<li><p>Interface URL: swap-api/v1/swap_settlement_records</p></li>
</ul>
<h3 id="2-added-fields-of-return-parameter-for-quot-query-liquidation-orders-quot-interface-amount-are-added-for-return-parameter-data-quot-quot-amount-quot-represents-the-liquidation-amount-token">2、Added fields of return parameter for "Query Liquidation Orders" interface（“amount” are added for return parameter “data". "amount" represents the liquidation amount (token);）</h3>
<ul>
<li><p>Interface Name: Query Liquidation Orders</p></li>
<li><p>Interface Type: public</p></li>
<li><p>Interface URL: swap-api/v1/swap_liquidation_orders</p></li>
</ul>
<h3 id="3-added-fields-of-return-parameter-for-quot-subscribe-liquidation-order-data-quot-interface-amount-are-added-for-return-parameter-data-quot-quot-amount-quot-represents-the-liquidation-amount-token">3、Added fields of return parameter for "Subscribe Liquidation Order Data" interface（“amount” are added for return parameter “data". "amount" represents the liquidation amount (token);）</h3>
<ul>
<li><p>Interface Name: Subscribe Liquidation Order Data</p></li>
<li><p>Interface Type: public</p></li>
<li><p>Subscription topic: public.$contract_code.liquidation_orders</p></li>
</ul>
<h2 id="1-1-0-2020-10-28-newly-added-query-financial-records-via-multiple-fields-query-history-orders-via-multiple-fields-query-history-transactions-via-multiple-fields">1.1.0 2020-10-28 【Newly added：Query financial records via multiple fields, Query history orders via multiple fields,Query history transactions via multiple fields.】</h2><h3 id="1-query-history-transactions-via-multiple-fields">1、Query history transactions via multiple fields</h3>
<ul>
<li><p>Interface Name：Query history transactions via multiple fields</p></li>
<li><p>Interface Type：private</p></li>
<li><p>Interface URL：swap-api/v1/swap_matchresults_exact</p></li>
</ul>
<h3 id="2-query-history-orders-via-multiple-fields">2、Query history orders via multiple fields</h3>
<ul>
<li><p>Interface Name：Query history orders via multiple fields</p></li>
<li><p>Interface Type：private</p></li>
<li><p>Interface URL：swap-api/v1/swap_hisorders_exact</p></li>
</ul>
<h3 id="3-query-financial-records-via-multiple-fields">3、Query financial records via multiple fields</h3>
<ul>
<li><p>Interface Name：Query financial records via multiple fields</p></li>
<li><p>Interface Type：private</p></li>
<li><p>Interface URL：swap-api/v1/swap_financial_record_exact</p></li>
</ul>
<h2 id="1-0-9-2020-10-15-newly-added-added-switch-leverage-interface-updated-websocket-messages-of-account-topic-will-be-pushed-when-leverage-switch-succeeds-websocket-messages-of-position-topic-will-be-pushed-when-leverage-switch-succeeds-new-response-fields-are-added-on-websocket-topic-of-match-orders-the-interface-swap_order_info-supports-query-of-4-hour-order-cancellation-data-previously-only-support-to-query-24-hour-data">1.0.9 2020-10-15 【Newly added：Added switch leverage interface; Updated:  websocket messages of account topic will be pushed when leverage switch succeeds;  websocket messages of position topic will be pushed when leverage switch succeeds; new response fields are added on websocket topic of match orders; the interface(swap_order_info) supports query of 4-hour order cancellation data (previously only support to query 24-hour data).】</h2><h3 id="1-added-switch-leverage-interface">1、Added switch leverage interface</h3>
<ul>
<li><p>Interface Name：Switch Leverage</p></li>
<li><p>Interface Type：private</p></li>
<li><p>Interface URL：swap-api/v1/swap_switch_lever_rate</p></li>
</ul>
<h3 id="2-subscribe-account-equity-updates-data-return-parameters-added-switch_lever_rate-event-type-to-represent-switching-leverages-when-the-leverage-is-successfully-switched-a-latest-information-on-assets-will-be-pushed-with-event-switch_lever_rate-quot">2、Subscribe Account Equity Updates Data（Return parameters added “switch_lever_rate” event type to represent switching leverages. When the leverage is successfully switched, a latest information on assets will be pushed with event“switch_lever_rate".）</h3>
<ul>
<li><p>Interface Name：Subscribe Account Equity Updates Data</p></li>
<li><p>Interface Type：private</p></li>
<li><p>Subscribe topic：accounts.$contract_code</p></li>
</ul>
<h3 id="3-subscribe-position-updates-return-parameters-added-switch_lever_rate-event-type-to-represent-switching-leverages-when-the-leverage-is-successfully-switched-a-latest-information-on-positions-will-be-pushed-with-event-switch_lever_rate-quot-the-information-will-not-be-pushed-when-the-user-39-s-position-is-0">3、Subscribe Position Updates（Return parameters added “switch_lever_rate” event type to represent switching leverages. When the leverage is successfully switched, a latest information on positions will be pushed with event“switch_lever_rate" (the information will not be pushed when the user's position is 0).）</h3>
<ul>
<li><p>Interface Name：Subscribe Position Updates</p></li>
<li><p>Interface Type：private</p></li>
<li><p>Subscribe topic：positions.$contract_code</p></li>
</ul>
<h3 id="4-subscribe-match-order-data-added-the-following-fields-in-return-parameters-direction-buy-sell-direction-offset-open-close-direction-lever_rate-leverages-price-order-price-created_at-creation-time-order_source-order-source-order_price_type-order-quotation-type">4、Subscribe Match Order Data （Added the following fields in return parameters: direction (buy/sell direction), offset (open/close direction), lever_rate (leverages), price (order price), created_at (creation time), order_source (order source), order_price_type (order quotation type).）</h3>
<ul>
<li><p>Interface Name：Subscribe Match Order Data</p></li>
<li><p>Interface Type：private</p></li>
<li><p>Subscribe topic：matchOrders.$contract_code </p></li>
</ul>
<h3 id="5-the-interface-swap_order_info-supports-query-of-4-hour-order-cancellation-data-previously-only-support-to-query-24-hour-data">5、The interface(swap_order_info) supports query of 4-hour order cancellation data (previously only support to query 24-hour data).</h3>
<ul>
<li><p>Interface Name：Get Information of an Order</p></li>
<li><p>Interface Type：private</p></li>
<li><p>Interface URL：swap-api/v1/swap_order_info</p></li>
</ul>
<h2 id="1-0-8-2020-10-10-newly-added-added-ws-interface-for-subscribing-system-status-updates-push">1.0.8 2020-10-10 【Newly added：Added WS interface for subscribing system status updates push】</h2><h3 id="1-added-ws-interface-for-subscribing-system-status-updates-push">1. Added WS interface for subscribing system status updates push</h3>
<ul>
<li>Interface name: subscribe system status updates</li>
<li>Interface type: public</li>
<li>Subscription topic：public.$service.heartbeat</li>
</ul>
<h2 id="1-0-7-2020-08-06-added-interfaces-subscribe-market-bbo-data-push-query-user-s-available-leverage-query-user-s-settlement-records-subscribe-trigger-orders-updates">1.0.7 2020-08-06 【Added interfaces：Subscribe market BBO data push； Query user’s available leverage；Query user’s settlement records；Subscribe trigger orders updates 】</h2><h3 id="1-subscribe-market-bbo-data">1、Subscribe Market BBO Data</h3>
<ul>
<li><p>Interface Name：Subscribe market BBO data push</p></li>
<li><p>Interface Type：public</p></li>
<li><p>Subscribe topic：market.$contract_code.bbo</p></li>
</ul>
<h3 id="2-query-user-s-available-leverage">2、 Query user’s available leverage</h3>
<ul>
<li><p>Interface Name： Query user’s available leverage</p></li>
<li><p>Interface Type：private</p></li>
<li><p>Interface URL：swap-api/v1/swap_available_level_rate</p></li>
</ul>
<h3 id="3-query-user-s-settlement-records">3、Query user’s settlement records</h3>
<ul>
<li><p>Interface Name：Query user’s settlement records</p></li>
<li><p>Interface Type：private</p></li>
<li><p>Interface URL：swap-api/v1/swap_user_settlement_records</p></li>
</ul>
<h3 id="4-subscribe-trigger-orders-updates">4、Subscribe trigger orders updates</h3>
<ul>
<li><p>Interface Name：Subscribe trigger orders updates</p></li>
<li><p>Interface Type：private</p></li>
<li><p>Subscribe topic：trigger_order.$contract_code</p></li>
</ul>
<h2 id="1-0-6-2020-06-19-update-added-client_order_id-in-outer-return-parameter">1.0.6 2020-06-19 【 Update: added client_order_id in outer return parameter 】</h2><h3 id="1-modified-perpetual-swaps-subscribe-match-order-data-interface-added-client_order_id-in-outer-return-parameter">1、Modified perpetual swaps subscribe match order data interface: added client_order_id in outer return parameter</h3>
<ul>
<li>Interface name: subscribe match order data</li>
<li>Interface type: private</li>
<li>Subscription topic: matchOrders.$contract_code</li>
</ul>
<h2 id="1-0-5-2020-06-14-add-interfaces-premium-index-kline-data-websocket-restful-estimated-funding-rate-kline-data-restful-websocket-basis-data-restful-websocket-update-interfaces-add-average-premium-index-of-querying-historical-funding-rates-add-four-depth-level-of-subscribing-market-depth-etc">1.0.5 2020-06-14  【 Add interfaces: Premium index Kline data(websocket, restful); Estimated funding rate Kline data(restful, websocket); Basis data (restful, websocket);Update interfaces: add average premium index of querying historical funding rates; add four depth level of subscribing market depth; etc】</h2><h3 id="1-add-an-interface-query-premium-index-kline-data">1、Add an interface: Query Premium Index Kline Data</h3>
<ul>
<li>Interface Name: Query Premium Index Kline Data</li>
<li>Interface Type: public interface</li>
<li>Interface URL: /index/market/history/swap_premium_index_kline</li>
</ul>
<h3 id="2-add-an-interface-subscribe-premium-index-kline-data">2、Add an interface: Subscribe Premium Index Kline Data</h3>
<ul>
<li>Interface Name: Subscribe Premium index Kline data</li>
<li>Interface Method: public interface</li>
<li>Subscribe Topic:  market.$contract_code.premium_index.$period</li>
</ul>
<h3 id="3-add-an-interface-request-premium-index-kline-data">3、Add an interface: Request Premium Index Kline Data</h3>
<ul>
<li>Interface Name: Request Premium index Kline data</li>
<li>Interface Method: public interface</li>
<li>Request Topic: market.$contract_code.premium_index.$period</li>
</ul>
<h3 id="4-add-an-interface-query-estimated-funding-rate-kline-data">4、Add an interface: Query Estimated Funding Rate Kline Data</h3>
<ul>
<li>Interface Name: Query Estimated funding rate Kline</li>
<li>Interface Type: public interface</li>
<li>Interface URL: /index/market/history/swap_estimated_rate_kline</li>
</ul>
<h3 id="5-add-an-interface-subscribe-estimated-funding-rate-kline-data">5、Add an interface: Subscribe Estimated Funding Rate Kline Data</h3>
<ul>
<li>Interface Name: Subscribe Estimated Funding Rate Kline</li>
<li>Interface Type: public interface</li>
<li>Subscribe Topic: market.$contract_code.estimated_rate.$period</li>
</ul>
<h3 id="6-add-an-interface-request-estimated-funding-rate-kline-data">6、Add an interface: Request Estimated Funding Rate Kline Data</h3>
<ul>
<li>Interface Name: Request estimated funding rate k line</li>
<li>Interface Type: public interface</li>
<li>Request Topic: market.$contract_code.estimated_rate.$period</li>
</ul>
<h3 id="7-add-an-interface-query-swap-basis-data">7、Add an interface: Query Swap Basis Data</h3>
<ul>
<li>Interface Name: Get basis data</li>
<li>Interface Type: public interface</li>
<li>Interface URL: /index/market/history/swap_basis</li>
</ul>
<h3 id="8-add-an-interface-subscribe-swap-basis-data">8、Add an interface: Subscribe Swap Basis Data</h3>
<ul>
<li>Interface Name: Subscribe basis data</li>
<li>Interface Type: public interface</li>
<li>Subscribe Topic: market.$contract_code.basis.$period.$basis_ price_type</li>
</ul>
<h3 id="9-add-an-interface-request-swap-basis-data">9、Add an interface: Request Swap Basis data</h3>
<ul>
<li>Interface Name: Request basis data</li>
<li>Interface Type: public interface</li>
<li>Request Topic:  market.$contract_code.basis.$period.$basis_ price_type</li>
</ul>
<h3 id="10-add-average-premuim-index-field-of-querying-historical-funding-rate">10、Add average premuim index field of querying historical funding rate</h3>
<ul>
<li>Interface Name: Query historical funding rate</li>
<li>Interface Type: public interface</li>
<li>Interface URL: /swap-api/v1/swap_historical_funding_rate</li>
</ul>
<h3 id="11-add-four-depth-level-of-subscribing-market-depth-step12-step13-step14-step15">11、Add Four depth level of subscribing Market Depth: step12,step13,step14,step15</h3>
<ul>
<li>Interface Name: Suscribe Market Depth</li>
<li>Interface Type: public interface</li>
<li>Interface URL: market.$contract_code.depth.$type</li>
</ul>
<h3 id="12-add-periodical-push-of-websocket-subscription-of-account-every-5s">12、Add periodical push of websocket subscription of account: every 5s</h3>
<ul>
<li>Interface Name: Subscribe Account</li>
<li>Interface Type: private interface</li>
<li>Interface URL: accounts.$contract_code</li>
</ul>
<h3 id="13-add-periodical-push-of-websocket-subscription-of-position-every-5s">13、Add periodical push of websocket subscription of position: every 5s</h3>
<ul>
<li>Interface Name: Subscribe Position</li>
<li>Interface Type: private interface</li>
<li>Interface URL: positions.$contract_code</li>
</ul>
<h3 id="14-add-return-fields-of-order-related-interfaces">14、Add return fields of order related interfaces:</h3><h4 id="14-1-add-fields-order_id-order_id_str-client_order_id-order_type-status-trade_avg_price-trade_turnover-trade_volume">14.1 Add fields: order_id, order_id_str, client_order_id, order_type, status, trade_avg_price, trade_turnover, trade_volume</h4>
<ul>
<li>Interface Name: Query Order Detail</li>
<li>Interface Type: private interface</li>
<li>Interface URL: swap-api/v1/swap_order_detail</li>
</ul>
<h4 id="14-2-add-fields-liquidation_type-canceled_at">14.2、Add fields: liquidation_type，canceled_at</h4>
<ul>
<li>Interface Name: Query Order Information</li>
<li>Interface Type: private interface</li>
<li>Interface URL: swap-api/v1/swap_order_info</li>
</ul>
<h4 id="14-3-add-fields-canceled_at-fee_asset">14.3、Add fields: canceled_at, fee_asset</h4>
<ul>
<li>Interface Name: Subscribe Orders</li>
<li>Interface Type: private interface</li>
<li>Subscribe Topic: orders.$contract_code</li>
</ul>
<h3 id="15-add-a-field-returned-by-websocket-subscription-of-private-topics-uid">15、Add a field returned by websocket subscription of private topics: uid</h3>
<ul>
<li>Interface Name: Subscribe Orders</li>
<li>Interface Type: private interface</li>
<li><p>Subscribe Topic: orders.$contract_code</p></li>
<li><p>Interface Name: Subscribe Accounts</p></li>
<li><p>Interface Type: private interface</p></li>
<li><p>Subscribe Topic: accounts.$contract_code</p></li>
<li><p>Interface Name: Subscribe Positions</p></li>
<li><p>Interface Type: private interface</p></li>
<li><p>Subscribe Topic: positions.$contract_code</p></li>
<li><p>Interface Name: Subscribe match Orders</p></li>
<li><p>Interface Type: private interface</p></li>
<li><p>Subscribe Topic: matchOrders.$contract_code</p></li>
</ul>
<h3 id="16-add-an-interface-place-a-trigger-order">16、Add an interface: place a trigger order</h3>
<ul>
<li>Interface Name: Place a trigger order</li>
<li>Interface Type: private interface</li>
<li>Interface URL: /swap-api/v1/swap_trigger_order</li>
</ul>
<h3 id="17-add-an-interface-cancel-trigger-order">17、Add an interface: Cancel trigger order</h3>
<ul>
<li>Interface Name: Cancel all trigger orders</li>
<li>Interface Type: private interface</li>
<li>Interface URL: /swap-api/v1/swap_trigger_cancel</li>
</ul>
<h3 id="18-add-an-interface-cancel-all-trigger-orders">18、Add an interface: Cancel all trigger orders</h3>
<ul>
<li>Interface Name: Cancel all trigger orders</li>
<li>Interface Type: private interface</li>
<li>Interface URL: /swap-api/v1/swap_trigger_cancelall</li>
</ul>
<h3 id="19-add-an-interface-query-open-trigger-orders">19、Add an interface: Query open trigger orders</h3>
<ul>
<li>Interface Name: Query open trigger orders</li>
<li>Interface Type: private interface</li>
<li>Interface URL: /swap-api/v1/swap_trigger_openorders</li>
</ul>
<h3 id="20-add-an-interface-query-historical-trigger-orders">20、Add an interface: Query historical trigger orders</h3>
<ul>
<li>Interface Name: Query historical trigger orders</li>
<li>Interface Type: private interface</li>
<li>Interface URL: /swap-api/v1/swap_trigger_hisorders</li>
</ul>
<h3 id="21-add-an-interface-subscribe-match-orders">21、Add an interface: Subscribe Match Orders</h3>
<ul>
<li>Interface Name: Subscribe Match Orders</li>
<li>Interface Type: private interface</li>
<li>Subscribe Topic: matchOrders.$contract_code</li>
</ul>
<h2 id="1-0-4-2020-5-27-add-an-interface-websocket-subscription-of-contract-info">1.0.4 2020-5-27 【 Add an interface: websocket subscription of contract info 】</h2><h3 id="1-add-an-interface-websocket-subscription-of-contract-info-event">1、Add an interface: websocket subscription of contract info event</h3>
<ul>
<li><p>Interface Name: websocket subscription of contract info event</p></li>
<li><p>Interface Type: public interface.</p></li>
<li><p>Subscription topic: public.$contract_code.contract_info</p></li>
</ul>
<h2 id="1-0-3-2020-05-07-add-an-interface-query-assets-and-position-info">1.0.3 2020-05-07 【 Add an interface: query assets and position info】</h2><h3 id="1-add-an-interface-query-assets-and-position-info">1、Add an interface: query assets and position info</h3>
<ul>
<li><p>Interface Name: query assets and position info</p></li>
<li><p>Interface Type: Private interface.</p></li>
<li><p>Interface URL： /swap-api/v1/swap_account_position_info</p></li>
</ul>
<h2 id="1-0-2-2020-04-09-add-an-interface-perpetual-swaps-funding-rate-ws-push-without-authentication-2-add-an-interface-perpetual-swaps-liquidation-order-ws-push-without-authentication">1.0.2 2020-04-09 [Add an interface: perpetual swaps funding rate WS push without authentication;2.   Add an interface: perpetual swaps liquidation order WS push without authentication]</h2><h3 id="1-add-an-interface-perpetual-swaps-funding-rate-ws-push-without-authentication">1、Add an interface: perpetual swaps funding rate WS push without authentication.</h3>
<ul>
<li>Interface name: Subscribe funding rate (no authentication) </li>
<li>Interface type: public interface.</li>
<li>Subscribe topic: public.$contract_code.funding_rate</li>
</ul>
<h3 id="2-add-an-interface-perpetual-swaps-liquidation-order-ws-push-without-authentication">2、    Add an interface: perpetual swaps liquidation order WS push without authentication</h3>
<ul>
<li>Interface name: Subscribe liquidation orders (no authentication)</li>
<li>Interface type: public interface.</li>
<li>Subscribe topic: public.$contract_code.liquidation_orders</li>
</ul>
<h2 id="1-0-1-2020-03-20">1.0.1 2020-03-20</h2><h3 id="1-log-in-with-your-master-account-on-web-to-sign-the-high-leverage-agreement-if-you-use-high-leverage-gt-20x-for-the-first-time-afterwards-you-can-place-order-by-api-with-high-leverage-gt-20x">1、Log in with your master account on Web to sign the High Leverage Agreement if you use high leverage (&gt;20x) for the first time. Afterwards, you can place order by API with high leverage (&gt;20x).</h3><h3 id="2-the-authentication-path-of-the-websocket-subscription-of-order-and-user-data-is-changed-from-39-notification-39-to-39-swap-notification-39">2、The authentication path of the websocket subscription of order and user data is changed from '/notification' to '/swap-notification'.</h3>
<ul>
<li>Interface name: All interfaces under the websocket subscription of order and user data.</li>
<li>Interface type: User private interface.</li>
<li>Authentication path: /swap-notification.</li>
</ul>
<h3 id="3-added-incremental-websocket-subscription-of-orderbook-data-orderbook-event-will-be-checked-every-30ms-if-there-is-no-orderbook-event-you-will-not-receive-any-orderbook-data">3、Added incremental websocket subscription of orderbook data.orderbook event will be checked every 30ms.If there is no orderbook event, you will not receive any orderbook data.</h3>
<ul>
<li>Interface Name: Subscribe Incremental Market Depth Data.</li>
<li>Interface type: public interface.</li>
<li>Subscribe Topic: market.$contract_code.depth.size_${size}.high_freq.</li>
</ul>
<h3 id="4-added-api-interface-of-querying-user-39-s-api-indicator-disable-information">4、Added API interface of querying user's API indicator disable information</h3>
<ul>
<li>Interface name: Query user's API indicator disable information</li>
<li>Interface type: User private interface </li>
<li>URL: /swap-api/v1/swap_api_trading_status</li>
</ul>
<h3 id="5-added-websocket-subscription-of-funding-rate-it-will-be-pushed-once-the-funding-rate-is-updated">5、 Added websocket subscription of funding rate.It will be pushed once the funding rate is updated.</h3>
<ul>
<li>Interface name: Subscribe funding rate</li>
<li>Interface type: User private interface</li>
<li>Subscribe Topic: funding_rate.$contract_code</li>
</ul>
<h3 id="6-modified-on-the-interface-of-querying-contract-information-on-order-limit-added-10-order-price-types-including-opponent_ioc-lightning_ioc-optimal_5_ioc-optimal_10_ioc-optimal_20_ioc-opponent_fok-lightning_fok-optimal_5_fok-optimal_10_fok-optimal_20_fok">6、Modified on the interface of querying contract information on order limit: added 10 order price types including opponent_ioc, lightning_ioc, optimal_5_ioc, optimal_10_ioc，optimal_20_ioc，opponent_fok，lightning_fok，optimal_5_fok，optimal_10_fok，optimal_20_fok</h3>
<ul>
<li>Interface name: Query contract information on order limit</li>
<li>Interface type: User private interface</li>
<li>URL: POST /swap-api/v1/swap_order_limit</li>
</ul>
<h3 id="7-modified-on-the-interface-of-placing-an-order-added-8-order-price-types-including-opponent_ioc-optimal_5_ioc-optimal_10_ioc-optimal_20_ioc-opponent_fok-optimal_5_fok-optimal_10_fok-optimal_20_fok">7、Modified on the interface of placing an order: added 8 order price types, including opponent_ioc, optimal_5_ioc, optimal_10_ioc, optimal_20_ioc,  opponent_fok,optimal_5_fok, optimal_10_fok, optimal_20_fok.</h3>
<ul>
<li>Interface name: Place an order </li>
<li>Interface type: User private interface</li>
<li>URL: /swap-api/v1/swap_order</li>
</ul>
<h3 id="8-modified-on-the-interface-of-placing-a-batch-of-orders-added-8-order-price-types-including-opponent_ioc-optimal_5_ioc-optimal_10_ioc-optimal_20_ioc-opponent_fok-optimal_5_fok-optimal_10_fok-optimal_20_fok">8、Modified on the interface of placing a batch of orders: added 8 order price types, including opponent_ioc, optimal_5_ioc, optimal_10_ioc, optimal_20_ioc,  opponent_fok, optimal_5_fok, optimal_10_fok, optimal_20_fok。</h3>
<ul>
<li>Interface name: Place a batch of orders</li>
<li>Interface type: User private interface</li>
<li>URL: /swap-api/v1/swap_batchorder</li>
</ul>
<h3 id="9-modified-on-the-interface-of-placing-lightning-close-order-interface-added-string-quot-order_price_type-quot-including-values-lightning_ioc-lightning_fok-lightning">9、Modified on the interface of placing lightning close order interface: added string "order_price_type", including values: lightning_ioc, lightning_fok, lightning</h3>
<ul>
<li>Interface name: Place lightning close order</li>
<li>Interface type: User private interface</li>
<li>URL: /swap-api/v1/swap_lightning_close_position</li>
</ul>
<h3 id="10-modified-on-the-interface-of-querying-trade-details-for-an-order-added-string-quot-liquidation_type-quot">10、Modified on the interface of querying trade details for an order: added string "liquidation_type".</h3>
<ul>
<li>Interface name: Get trade details of an order</li>
<li>Interface type: User private interface</li>
<li>URL: POST /swap-api/v1/swap_order_detail</li>
</ul>
<h3 id="11-modified-quot-trade_type-quot-and-quot-orders-quot-in-the-interface-of-querying-history-orders-added-quot-reduce-positions-to-close-long-quot-and-quot-reduce-positions-to-close-short-quot-types-in-request-parameter-quot-trade_type-quot-added-string-quot-liquidation_type-quot-in-orders-array-of-returning-parameter">11、Modified "trade_type" and "orders" in the interface of querying history orders. Added "reduce positions to close long" and "reduce positions to close short" types in request parameter "trade_type"; Added string "liquidation_type" in orders array of returning parameter.</h3>
<ul>
<li>Interface name: Query history orders interface.</li>
<li>Interface type: User private interface</li>
<li>URL: POST /swap-api/v1/swap_hisorders</li>
</ul>
<h3 id="12-added-string-quot-liquidation_type-quot-in-order-transaction-push-in-websocket-subscription">12、Added string "liquidation_type" in order transaction push in WebSocket Subscription.</h3>
<ul>
<li>Interface name: Match result on order push in WebSocket subscription</li>
<li>Interface type: User private interface</li>
<li>Subscribe Topic: orders.$contract_code</li>
</ul>
<h3 id="13-added-an-interface-transfer-between-master-account-and-sub-accounts-the-rate-limit-between-the-master-account-and-each-subaccount-is-10-times-minute-interface-name-transfer-between-master-account-and-sub-accounts">13、Added an interface: transfer between master account and sub-accounts, the rate limit between the master account and each subaccount is 10 times/ minute.Interface name: Transfer between master account and sub-accounts.</h3>
<ul>
<li>Interface name: transfer between master account and sub-accounts</li>
<li>Interface type: User private interface</li>
<li>URL：/swap-api/v1/swap_master_sub_transfer</li>
</ul>
<h3 id="14-added-a-parameter-transfer-permission-between-master-account-and-sub-accounts-added-strings-quot-master_transfer_sub-quot-and-quot-sub_transfer_master-quot-in-returning-parameter-data-array">14、Added a parameter: transfer permission between master account and sub-accounts. Added strings: "master_transfer_sub" and "sub_transfer_master" in returning parameter data array.</h3>
<ul>
<li>Interface name: Query information on system status</li>
<li>Interface type: Public</li>
<li>URL：/swap-api/v1/swap_api_state</li>
</ul>
<h3 id="15-added-an-interface-query-transfer-records-of-master-account-and-sub-accounts">15、Added an interface: query transfer records of master account and sub-accounts.</h3>
<ul>
<li>Interface name: Query transfer records of master account and sub-accounts.</li>
<li>Interface type: User private interface</li>
<li>URL: /swap-api/v1/swap_master_sub_transfer_record</li>
</ul>
<h3 id="16-added-four-kinds-of-transfer-statements-between-master-account-and-sub-accounts-in-returning-financial-record-interface">16、Added four kinds of transfer statements between master account and sub-accounts in returning financial record interface.</h3>
<ul>
<li>Interface name: Query contract financial record</li>
<li>Interface type: User private interface</li>
<li>URL: /swap-api/v1/swap_financial_record</li>
</ul>
<h1 id="swap-api-access-guide">Swap API Access Guide</h1><h2 id="api-list">API List</h2>
<table><thead>
<tr>
<th>permission type</th>
<th>Content Type</th>
<th>Context</th>
<th>Request Type</th>
<th>Desc</th>
<th>Signature Required</th>
</tr>
</thead><tbody>
<tr>
<td>Read</td>
<td>Market Data</td>
<td>/swap-api/v1/swap_contract_info</td>
<td>GET</td>
<td>Query Swap Info</td>
<td>No</td>
</tr>
<tr>
<td>Read</td>
<td>Market Data</td>
<td>/swap-api/v1/swap_index</td>
<td>GET</td>
<td>Query Swap Index Price Information</td>
<td>No</td>
</tr>
<tr>
<td>Read</td>
<td>Market Data</td>
<td>/swap-api/v1/swap_price_limit</td>
<td>GET</td>
<td>Query Swap Price Limitation</td>
<td>No</td>
</tr>
<tr>
<td>Read</td>
<td>Market Data</td>
<td>/swap-api/v1/swap_open_interest</td>
<td>GET</td>
<td>Get Swap Open Interest Information</td>
<td>No</td>
</tr>
<tr>
<td>Read</td>
<td>Market Data</td>
<td>/swap-api/v1/swap_delivery_price</td>
<td>GET</td>
<td>Get the estimated delivery price</td>
<td>No</td>
</tr>
<tr>
<td>Read</td>
<td>Market Data</td>
<td>/swap-api/v1/swap_api_state</td>
<td>GET</td>
<td>Query information on system status</td>
<td>No</td>
</tr>
<tr>
<td>Read</td>
<td>Market Data</td>
<td>/swap-ex/market/depth</td>
<td>GET</td>
<td>Get Market Depth</td>
<td>No</td>
</tr>
<tr>
<td>Read</td>
<td>Market Data</td>
<td>/swap-ex/market/history/kline</td>
<td>GET</td>
<td>Get KLine Data</td>
<td>No</td>
</tr>
<tr>
<td>Read</td>
<td>Market Data</td>
<td>/index/market/history/swap_mark_price_kline</td>
<td>GET</td>
<td>Get Kline Data of Mark Price</td>
<td>No</td>
</tr>
<tr>
<td>Read</td>
<td>Market Data</td>
<td>/swap-ex/market/detail/merged</td>
<td>GET</td>
<td>Get Market Data Overview</td>
<td>No</td>
</tr>
<tr>
<td>Read</td>
<td>Market Data</td>
<td>/swap-ex/market/detail/batch_merged</td>
<td>GET</td>
<td>Get a Batch of Market Data Overview</td>
<td>No</td>
</tr>
<tr>
<td>Read</td>
<td>Market Data</td>
<td>/swap-ex/market/trade</td>
<td>GET</td>
<td>Query The Last Trade of a Contract</td>
<td>No</td>
</tr>
<tr>
<td>Read</td>
<td>Market Data</td>
<td>/swap-ex/market/history/trade</td>
<td>GET</td>
<td>Query a Batch of Trade Records of a Contract</td>
<td>No</td>
</tr>
<tr>
<td>Read</td>
<td>Market Data</td>
<td>/swap-api/v1/swap_risk_info</td>
<td>GET</td>
<td>Query information on contract insurance fund balance and estimated clawback rate</td>
<td>No</td>
</tr>
<tr>
<td>Read</td>
<td>Market Data</td>
<td>/swap-api/v1/swap_insurance_fund</td>
<td>GET</td>
<td>Query history records of insurance fund balance</td>
<td>No</td>
</tr>
<tr>
<td>Read</td>
<td>Market Data</td>
<td>/swap-api/v1/swap_adjustfactor</td>
<td>GET</td>
<td>Query information on Tiered Adjustment Factor</td>
<td>No</td>
</tr>
<tr>
<td>Read</td>
<td>Market Data</td>
<td>/swap-api/v1/swap_his_open_interest</td>
<td>GET</td>
<td>Query information on open interest</td>
<td>No</td>
</tr>
<tr>
<td>Read</td>
<td>Market Data</td>
<td>/swap-api/v1/swap_elite_account_ratio</td>
<td>GET</td>
<td>Query Top Trader Sentiment Index Function-Account</td>
<td>No</td>
</tr>
<tr>
<td>Read</td>
<td>Market Data</td>
<td>/swap-api/v1/swap_elite_position_ratio</td>
<td>GET</td>
<td>Query Top Trader Sentiment Index Function-Position</td>
<td>No</td>
</tr>
<tr>
<td>Read</td>
<td>Market Data</td>
<td>/swap-api/v1/swap_liquidation_orders</td>
<td>GET</td>
<td>Query Liquidation Orders</td>
<td>No</td>
</tr>
<tr>
<td>Read</td>
<td>Market Data</td>
<td>swap-api/v1/swap_settlement_records</td>
<td>GET</td>
<td>Query historical settlement records of the platform interface</td>
<td>No</td>
</tr>
<tr>
<td>Read</td>
<td>Market Data</td>
<td>/index/market/history/swap_premium_index_kline</td>
<td>GET</td>
<td>Query Premium Index Kline Data</td>
<td>No</td>
</tr>
<tr>
<td>Read</td>
<td>Market Data</td>
<td>/index/market/history/swap_basis</td>
<td>GET</td>
<td>Query Basis Data</td>
<td>No</td>
</tr>
<tr>
<td>Read</td>
<td>Market Data</td>
<td>/swap-api/v1/swap_batch_funding_rate</td>
<td>GET</td>
<td>Query a Batch of Funding Rate</td>
<td>No</td>
</tr>
<tr>
<td>Read</td>
<td>Market Data</td>
<td>/swap-api/v1/swap_historical_funding_rate</td>
<td>GET</td>
<td>Query historical funding rate</td>
<td>No</td>
</tr>
<tr>
<td>Read</td>
<td>Market Data</td>
<td>/swap-api/v1/swap_estimated_settlement_price</td>
<td>GET</td>
<td>Get the estimated settlement price</td>
<td>No</td>
</tr>
<tr>
<td>Read</td>
<td>Market Data</td>
<td>/swap-api/v1/swap_ladder_margin</td>
<td>GET</td>
<td>Query information on Tiered Margin interface</td>
<td>No</td>
</tr>
<tr>
<td>Read</td>
<td>Account</td>
<td>/swap-api/v1/swap_balance_valuation</td>
<td>POST</td>
<td>Query Asset Valuation</td>
<td>Yes</td>
</tr>
<tr>
<td>Read</td>
<td>Account</td>
<td>/swap-api/v1/swap_account_info</td>
<td>POST</td>
<td>Query User’s Account Information</td>
<td>Yes</td>
</tr>
<tr>
<td>Read</td>
<td>Account</td>
<td>/swap-api/v1/swap_position_info</td>
<td>POST</td>
<td>Query User’s position Information</td>
<td>Yes</td>
</tr>
<tr>
<td>Trade</td>
<td>Account</td>
<td>/swap-api/v1/swap_sub_auth</td>
<td>POST</td>
<td>Set a Batch of Sub-Account Trading Permissions</td>
<td>Yes</td>
</tr>
<tr>
<td>Read</td>
<td>Account</td>
<td>/swap-api/v1/swap_sub_account_list</td>
<td>POST</td>
<td>Query assets information of all sub-accounts under the master account (Query by coins)</td>
<td>Yes</td>
</tr>
<tr>
<td>Read</td>
<td>Account</td>
<td>/swap-api/v1/swap_sub_account_info_list</td>
<td>POST</td>
<td>Query a Batch of Sub-Account's Assets Information</td>
<td>Yes</td>
</tr>
<tr>
<td>Read</td>
<td>Account</td>
<td>/swap-api/v1/swap_sub_account_info</td>
<td>POST</td>
<td>Query a single sub-account's assets information</td>
<td>Yes</td>
</tr>
<tr>
<td>Read</td>
<td>Account</td>
<td>/swap-api/v1/swap_sub_position_info</td>
<td>POST</td>
<td>Query a single sub-account's position information</td>
<td>Yes</td>
</tr>
<tr>
<td>Read</td>
<td>Account</td>
<td>/swap-api/v1/swap_financial_record</td>
<td>POST</td>
<td>Query account financial records</td>
<td>Yes</td>
</tr>
<tr>
<td>Read</td>
<td>Account</td>
<td>swap-api/v1/swap_financial_record_exact</td>
<td>POST</td>
<td>Query financial records via multiple fields</td>
<td>Yes</td>
</tr>
<tr>
<td>Read</td>
<td>Account</td>
<td>swap-api/v1/swap_user_settlement_records</td>
<td>POST</td>
<td>Query user’s settlement records</td>
<td>Yes</td>
</tr>
<tr>
<td>Read</td>
<td>Account</td>
<td>swap-api/v1/swap_available_level_rate</td>
<td>POST</td>
<td>Query user’s available leverage</td>
<td>Yes</td>
</tr>
<tr>
<td>Read</td>
<td>Account</td>
<td>/swap-api/v1/swap_order_limit</td>
<td>POST</td>
<td>Query contract information on order limit</td>
<td>Yes</td>
</tr>
<tr>
<td>Read</td>
<td>Account</td>
<td>/swap-api/v1/swap_fee</td>
<td>POST</td>
<td>Query information on contract trading fee</td>
<td>Yes</td>
</tr>
<tr>
<td>Read</td>
<td>Account</td>
<td>/swap-api/v1/swap_transfer_limit</td>
<td>POST</td>
<td>Query information on Transfer Limit</td>
<td>Yes</td>
</tr>
<tr>
<td>Read</td>
<td>Account</td>
<td>/swap-api/v1/swap_position_limit</td>
<td>POST</td>
<td>Query information on position limit</td>
<td>Yes</td>
</tr>
<tr>
<td>Read</td>
<td>Account</td>
<td>/swap-api/v1/swap_master_sub_transfer_record</td>
<td>GET</td>
<td>Query transfer records of master account</td>
<td>No</td>
</tr>
<tr>
<td>Trade</td>
<td>Account</td>
<td>/swap-api/v1/swap_master_sub_transfer</td>
<td>POST</td>
<td>transfer between master account and sub-accounts</td>
<td>No</td>
</tr>
<tr>
<td>Trade</td>
<td>Trade</td>
<td>/swap-api/v1/swap_order</td>
<td>POST</td>
<td>Place an Order</td>
<td>Yes</td>
</tr>
<tr>
<td>Trade</td>
<td>Trade</td>
<td>/swap-api/v1/swap_batchorder</td>
<td>POST</td>
<td>Place a Batch of Orders</td>
<td>Yes</td>
</tr>
<tr>
<td>Trade</td>
<td>Trade</td>
<td>/swap-api/v1/swap_cancel</td>
<td>POST</td>
<td>Cancel an Order</td>
<td>Yes</td>
</tr>
<tr>
<td>Trade</td>
<td>Trade</td>
<td>/swap-api/v1/swap_cancelall</td>
<td>POST</td>
<td>Cancel All Orders</td>
<td>Yes</td>
</tr>
<tr>
<td>Trade</td>
<td>Trade</td>
<td>/swap-api/v1/swap_switch_lever_rate</td>
<td>POST</td>
<td>Switch Leverage</td>
<td>Yes</td>
</tr>
<tr>
<td>Trade</td>
<td>Trade</td>
<td>/swap-api/v1/swap_lightning_close_position</td>
<td>POST</td>
<td>Place Lightning Close Order</td>
<td>Yes</td>
</tr>
<tr>
<td>Trade</td>
<td>Strategy</td>
<td>/swap-api/v1/swap_trigger_order</td>
<td>POST</td>
<td>Place an Trigger Order</td>
<td>Yes</td>
</tr>
<tr>
<td>Trade</td>
<td>Strategy</td>
<td>/swap-api/v1/swap_trigger_cancel</td>
<td>POST</td>
<td>Cancel a Trigger Order</td>
<td>Yes</td>
</tr>
<tr>
<td>Trade</td>
<td>Strategy</td>
<td>swap-api/v1/swap_trigger_cancelall</td>
<td>POST</td>
<td>Cancel all trigger Orders</td>
<td>Yes</td>
</tr>
<tr>
<td>Read</td>
<td>Strategy</td>
<td>swap-api/v1/swap_trigger_openorders</td>
<td>POST</td>
<td>Get all open trigger Orders</td>
<td>Yes</td>
</tr>
<tr>
<td>Read</td>
<td>Strategy</td>
<td>swap-api/v1/swap_trigger_hisorders</td>
<td>POST</td>
<td>Get all history trigger Orders</td>
<td>Yes</td>
</tr>
<tr>
<td>Read</td>
<td>Trade</td>
<td>/swap-api/v1/swap_order_info</td>
<td>POST</td>
<td>Get Information of an Order</td>
<td>Yes</td>
</tr>
<tr>
<td>Read</td>
<td>Trade</td>
<td>/swap-api/v1/swap_order_detail</td>
<td>POST</td>
<td>Get Trade Details of an Order</td>
<td>Yes</td>
</tr>
<tr>
<td>Read</td>
<td>Trade</td>
<td>/swap-api/v1/swap_openorders</td>
<td>POST</td>
<td>Get Current Orders</td>
<td>Yes</td>
</tr>
<tr>
<td>Read</td>
<td>Trade</td>
<td>/swap-api/v1/swap_hisorders</td>
<td>POST</td>
<td>Get History Orders</td>
<td>Yes</td>
</tr>
<tr>
<td>Read</td>
<td>Trade</td>
<td>/swap-api/v1/swap_hisorders_exact</td>
<td>POST</td>
<td>Query history orders via multiple fields</td>
<td>Yes</td>
</tr>
<tr>
<td>Read</td>
<td>Trade</td>
<td>/swap-api/v1/swap_matchresults</td>
<td>POST</td>
<td>Acquire History Match Results</td>
<td>Yes</td>
</tr>
<tr>
<td>Read</td>
<td>Trade</td>
<td>/swap-api/v1/swap_matchresults_exact</td>
<td>POST</td>
<td>Query history transactions via multiple fields</td>
<td>Yes</td>
</tr>
<tr>
<td>Trade</td>
<td>Strategy</td>
<td>/swap-api/v1/swap_tpsl_order</td>
<td>POST</td>
<td>Set a Take-profit and Stop-loss Order for an Existing Position</td>
<td>Yes</td>
</tr>
<tr>
<td>Trade</td>
<td>Strategy</td>
<td>/swap-api/v1/swap_tpsl_cancel</td>
<td>POST</td>
<td>Cancel a Take-profit and Stop-loss Order</td>
<td>Yes</td>
</tr>
<tr>
<td>Trade</td>
<td>Strategy</td>
<td>/swap-api/v1/swap_tpsl_cancelall</td>
<td>POST</td>
<td>Cancel all Take-profit and Stop-loss Orders</td>
<td>Yes</td>
</tr>
<tr>
<td>Read</td>
<td>Strategy</td>
<td>/swap-api/v1/swap_tpsl_openorders</td>
<td>POST</td>
<td>Open take-profit and stop-loss orders</td>
<td>Yes</td>
</tr>
<tr>
<td>Read</td>
<td>Strategy</td>
<td>/swap-api/v1/swap_tpsl_hisorders</td>
<td>POST</td>
<td>Take-profit and stop-loss histoty orders</td>
<td>Yes</td>
</tr>
<tr>
<td>Read</td>
<td>Strategy</td>
<td>/swap-api/v1/swap_relation_tpsl_order</td>
<td>POST</td>
<td>Query Info Of Take-profit and Stop-loss Order That Related To Position Opening Order</td>
<td>Yes</td>
</tr>
</tbody></table>
<h2 id="address">Address</h2>
<table><thead>
<tr>
<th>Address</th>
<th>Applicable sites</th>
<th>Applicable functions</th>
<th>Applicable trading pairs</th>
</tr>
</thead><tbody>
<tr>
<td>https://api.hbdm.com</td>
<td>Huobi Coin Margined Swap</td>
<td>API</td>
<td>Trading pairs provided by Huobi Coin Margined Swap</td>
</tr>
</tbody></table>
<h3 id="notice">Notice</h3>
<p>If you can't connect "https://api.hbdm.com", please use "https://api.btcgateway.pro" for debug purpose. If your server is deployed in AWS, we recommend using "https://api.hbdm.vn".</p>
<h2 id="signature-authentication-amp-verification">Signature Authentication &amp; Verification</h2><h3 id="signature-guide">Signature Guide</h3>
<p>Considering that API requests may get tampered in the process of transmission, to keep the transmission secure, you have to use your API Key to do Signature Authentication for all private interface except for public interface (used for acuqiring basic information and market data), in this way to verify whether the parameters/ parameter value get tampered or not in the process of transmission</p>

<p>A legitimate request consists of following parts：</p>

<ul>
<li><p>Request address of method, i.e. visit server address--api.hbdm.com, e.g.:  api.hbdm.com/swap-api/v1/swap_order</p></li>
<li><p>API Access Key ID (AccessKeyId): Access Key of the API Key that you apply.</p></li>
<li><p>Method of Signature (SignatureMethod): Based on the Hash Aggrement, users calculate the signature via HmacSHA256.</p></li>
<li><p>Signature Version (SignatureVersion): It adopts version 2 in terms of Signature Version.</p></li>
<li><p>Timestamp (Timestamp): The time when you send the request (UTC time zone) : (UTC time zone) : (UTC time zone), e.g.: 2017-05-11T16:22:06</p></li>
<li><p>Must-fill parameters &amp; optional parameters: For each method, there are a group of must-fill parameters and optional parameters used to address the API request, which can be found in the illustration of each method as well as their meaning. Please note that, in terms of "Get" requests, it needs to do Signature calculation for all the original parameters in each method ; In terms of "Post" requests, no need to do Signature calculation for the original parameters in each method, which means only four parameters need to do Signature calculation in "Post" requests, i.e. AccessKeyId, SignatureMethod, SignatureVersion, Timestamp with other parameters placed in "body".</p></li>
<li><p>Signature: The result of Signature calculation which is used to verify if signature is valid and not tampered.</p></li>
</ul>
<h3 id="create-api-key">Create API Key</h3>
<p><a href="https://www.hbg.com/zh-cn/apikey/">You could  create API Key at</a></p>

<p>API Key consists of the following two parts.</p>

<ul>
<li><p>"Access Key", the Key used to visit API.</p></li>
<li><p>"Secret Key", the Key used to do Signature authentication and verification (visible during application period).</p></li>
</ul>

<aside class="notice">
When create API Key, users could bind IP address, as the validity of unbond IP address is only 90 days.
</aside>

<aside class="notice">
API Key has operation authorization of trading, borrowing, deposit and withdrawal etc..
</aside>

<aside class="warning">
Both Access Key and Secret Key are closely related with account security, please do not disclose them to others for any reasons anytime.
</aside>
<h3 id="steps-for-signature">Steps for Signature</h3>
<p>Normative request for Signature calculation     Different contents will get totally different results when use HMAC to calculate Signature, therefore, please normalize the requests before doing Signature calculation. Take the request of inquering order details as an example:</p>

<p>query details of one order </p>

<p><code>https://api.hbdm.com/swap-api/v1/swap_order?</code></p>

<p><code>AccessKeyId=e2xxxxxx-99xxxxxx-84xxxxxx-7xxxx</code></p>

<p><code>&amp;SignatureMethod=HmacSHA256</code></p>

<p><code>&amp;SignatureVersion=2</code></p>

<p><code>&amp;Timestamp=2017-05-11T15:19:30</code></p>
<h4 id="1-request-methods-get-post-add-line-breaker-quot-n-quot">1. Request methods (GET/POST): add line breaker "\n".</h4>
<p><code>POST\n</code></p>
<h4 id="2-text-the-visit-address-in-lowercase-adding-line-breake-quot-n-quot">2. Text the visit address in lowercase, adding line breake "\n"</h4>
<p><code>
api.hbdm.com\n
</code></p>
<h4 id="3-visit-the-path-of-methods-adding-line-breaker-quot-n-quot">3. Visit the path of methods, adding line breaker "\n"</h4>
<p><code>
//swap-api/v1/swap_order\n
</code></p>
<h4 id="4-rank-the-parameter-names-according-to-the-sequence-of-ascii-codes-for-example-below-is-the-parameters-in-original-sequence-and-the-new-sequence">4. Rank the parameter names according to the sequence of ASCII codes, for example, below is the parameters in original sequence and the new sequence:</h4>
<p><code>AccessKeyId=e2xxxxxx-99xxxxxx-84xxxxxx-7xxxx</code></p>

<p><code>SignatureMethod=HmacSHA256</code></p>

<p><code>SignatureVersion=2</code></p>

<p><code>Timestamp=2017-05-11T15%3A19%3A30</code></p>

<aside class="notice">
Use UTF-8 to encode when it has already been encoded by URI with hexadecimals in Uppercase, e.g., ":" wiil be encoded to "%3A" while space to "%20".
</aside>

<aside class="notice">
Timestamp should be written in the form of YYYY-MM-DDThh:mm:ss and encoded with URI.
</aside>
<h4 id="5-after-ranking">5.After ranking</h4>
<p><code>AccessKeyId=e2xxxxxx-99xxxxxx-84xxxxxx-7xxxx</code></p>

<p><code>SignatureMethod=HmacSHA256</code></p>

<p><code>SignatureVersion=2</code></p>

<p><code>Timestamp=2017-05-11T15%3A19%3A30</code></p>
<h4 id="6-following-the-sequence-above-link-parameters-with-quot-amp-quot">6.Following the sequence above, link parameters with "&amp;"</h4>
<p><code>AccessKeyId=e2xxxxxx-99xxxxxx-84xxxxxx-7xxxx&amp;SignatureMethod=HmacSHA256&amp;SignatureVersion=2&amp;Timestamp=2017-05-11T15%3A19%3A30</code></p>
<h4 id="7-form-the-final-character-strings-that-need-to-do-signature-calculation-as-following">7. Form the final character strings that need to do Signature calculation as following:</h4>
<p><code>POST\n</code></p>

<p><code>api.hbdm.com\n</code></p>

<p><code>//swap-api/v1/swap_order\n</code></p>

<p><code>AccessKeyId=e2xxxxxx-99xxxxxx-84xxxxxx-7xxxx&amp;SignatureMethod=HmacSHA256&amp;SignatureVersion=2&amp;Timestamp=2017-05-11T15%3A19%3A30</code></p>
<h4 id="8-use-the-quot-request-character-strings-quot-formed-in-the-last-step-and-your-secret-key-to-create-a-digital-signature">8. Use the "request character strings" formed in the last step and your Secret Key to create a digital Signature.</h4>
<p><code>4F65x5A2bLyMWVQj3Aqp+B4w+ivaA7n5Oi2SuYtCJ9o=</code></p>

<ol>
<li><p>Take the request character string formed in the last step and API Secret Key as two parameters, encoding them with the Hash Function HmacSHA256 to get corresponding Hash value.</p></li>
<li><p>Encoding the Hash value with base-64 code, the result will be the digital Signature of this request.</p></li>
</ol>
<h4 id="9-add-the-digital-signature-into-the-parameters-of-request-path">9. Add the digital Signature into the parameters of request path.</h4>
<p>The final request sent to Server via API should be like:</p>

<p><code>https://api.hbdm.com/swap-api/v1/swap_order?AccessKeyId=e2xxxxxx-99xxxxxx-84xxxxxx-7xxxx&amp;order-id=1234567890&amp;SignatureMethod=HmacSHA256&amp;SignatureVersion=2&amp;Timestamp=2017-05-11T15%3A19%3A30&amp;Signature=4F65x5A2bLyMWVQj3Aqp%2BB4w%2BivaA7n5Oi2SuYtCJ9o%3D</code></p>

<ol>
<li><p>Add all the must authentication parameters into the parameters of request path;</p></li>
<li><p>Add the digital Signature encoded with URL code into the path parameters with the parameter name of "Signature".</p></li>
</ol>
<h2 id="api-rate-limit-illustration">API Rate Limit Illustration</h2>
<p>Future, Coin Margined Swap,Option Swap and USDT Margined Swap are using separate API rate limits.</p>

<p>Please note that, for both public interface and private interface, there are rate limits, more details are as below:</p>

<ul>
<li><p>Generally, the private interface rate limit of API key is at most 72 times every 3 seconds for each UID (Trade Interface: at most 36 times every 3 seconds. Read Interface: at most 36 times every 3 seconds) (this rate limit is shared by all the altcoins contracts delivered by different date).<a href="https://docs.huobigroup.com/docs/coin_margined_swap/v1/en/#api-list"> API Interface List </a> </p></li>
<li><p>For public interface used to get information of index, price limit, settlement, delivery, open positions and so on, the rate limit is 120 times every 3 second at most for each IP (this 120 times every 3 second public interface rate limit is shared by all the requests from that IP of non-marketing information, like above).</p></li>
<li><p>For public interface to get market data such as  Get Kline data, Get Market Data Overview, Get Contract Information,Get market in-depth data, Get premium index Kline, Get real-time forecast capital rate kline, Get basis data, Get the last Trade of a Contract and so on：</p>

<p>(1) For restful interfaces：all products(futures, coin margined swap, usdt margined swap and option) 800 times/second for one IP at most</p>

<p>（2）For websocket: The rate limit for “req” request is 50 times at once. No limit for “sub” request as the data will be pushed by sever voluntarily.</p></li>
<li><p>WebSocket, the private order push interface, requires API KEY Verification:</p>

<p>Each UID can build at most create 30 WS connections for private order push at the same time. For each account, 
contracts of the same underlying coin only need to subscribe one WS order push, e.g. users only need to create one WS 
order push connection for BTC Contract which will automatically push orders of BTC-USD
contracts. Please note that the rate limit of WS order push and RESTFUL private interface are separated from each other, with no relations.</p></li>
<li><p>Both read and trade interfaces will return the ratelimit info.You can refer to the following fields of "header" from api response. E.g.,you will get the total Read ratelimit("ratelimit-limit") and the remaining Read ratelimit("ratelimit-remaining") when you query the order info(/swap-api/v1/swap_account_info) , and you will get the total Trade ratelimit("ratelimit-limit") and the remaining Trade ratelimit("ratelimit-remaining") when you place an order(/swap-api/v1/swap_order)). <a href="https://docs.huobigroup.com/docs/coin_margined_swap/v1/en/#api-list"> API Interface List </a> </p></li>
<li><p>Will response following string for "header" via api </p>

<p>ratelimit-limit: the upper limit of requests per time, unit: times</p>

<p>ratelimit-interval: reset interval (reset the number of request), unit: ms</p>

<p>ratelimit-remaining: the left available request number for this round, unit: times</p>

<p>ratelimit-reset: upper limit of reset time used to reset request number, unit: ms </p>

<p>When API Limitation on Order Cancellation Ratio is triggered,the following string for "header" via api will also be returned:</p>

<p>recovery-time: recovery timestamp, whose unit is millisecond, showing the end time of prohibition, or the access retrieval timestamp; </p>

<p>if you are not in the prohibition period, the field is not included in returned header; </p></li>
</ul>
<h2 id="api-limitation-on-order-cancellation-ratio">API Limitation on Order Cancellation Ratio</h2>
<ul>
<li>The system will calculate the order cancellation ratio automatically when the total number of orders placed via certain order price types by the API user goes equal to or larger than 3,000 within 10 minutes. If the order cancellation ratio is greater than 99%, the user will be prohibited for 5 minutes from placing orders via certain API order price types which will be listed below (The response of placing orders will return: 1084  Your contract API is disabled, please try again after {0} (GMT+8).).</li>
<li>A 30-minute API order placement prohibition will be triggered if the user was prohibited for 3 times within an hour (The response of placing orders will return: 1084  Your contract API is disabled, please try again after {0} (GMT+8).). After resuming access, the total number of prohibited times will be cleared during the previous period and will not be counted into the total prohibited times in the new period.</li>
<li>Please note that the prohibition from placing orders will cause no effect on order cancellation via API as well as order placement and cancellation via other terminals. We’ll keep you notified on each prohibition via SMS and email.</li>
<li><p>Only four API order price types will be prohibited which are Limit order, Post_only, FOK and IOC. Please note that you can still use freely other order price types during the banned period, such as Lightning Close, BBO, Optimal 5, Optimal 10 and Optimal 20, opponent_ioc, lightning_ioc, optimal_5_ioc, optimal_10_ioc，optimal_20_ioc，opponent_fok，lightning_fok，optimal_5_fok，optimal_10_fok，optimal_20_fok,etc.</p></li>
<li><p>The response header returned by HTTP request:</p>

<ul>
<li>When placing order by using the four prohibited order price types during the prohibition period, the message header returned by interface will include the field: </li>
<li>"recovery-time": recovery timestamp,whose unit is millisecond, showing the end time of prohibition, or the access retrieval timestamp; </li>
<li>if you are not in the prohibition period, the field is not included in returned header;</li>
</ul></li>
<li><p>Please note that our system calculates order cancellation ratio according to UID and therefore, the master account UID and sub-accounts UIDs will be counted separately. The calculation period is 10 min/time(The start time starts at 00:00 and the end time is 00:10. Every 10 minutes is a cycle. ).</p></li>
<li><p>Definition of Indicators：</p>

<ul>
<li>Order Cancellation Ratio =Total number of invalid cancellation / Total number of placed orders (all types of orders placed via API) </li>
<li>Total number of placed order: Total number of placed orders refers to all orders placed via API which meet these requirements:</li>
<li>1.the order type is placing orders (Order Type = 1),</li>
<li>2.order price types include Limit Order, Post_only, FOK and IOC.</li>
<li>3.order creating time should be within the interval between 3 seconds before the start time of the calculation period and the end time of the calculation period.</li>
<li>Total number of invalid cancellation:Total number of invalid cancellation refers to all cancellation orders placed via API which meet the requirements.</li>
<li>the order type is placing orders (order Type=1),</li>
<li>the order price types are Limit Order, post_only, FOK and IOC.</li>
<li>the order status is “Orders cancelled” (status=7).</li>
<li>order with 0 fulfilled.</li>
<li>the interval between order cancellation and placement should be less than or equal to 3 seconds.</li>
<li>the order cancellation time should be within the calculation period.</li>
</ul></li>
<li><p>In order to ensure stability and transaction performance of API, please try to reduce order cancellation rate and cancellation amount during peak periods to avoid frequent triggering of API restriction mechanism.Suggestions of reducing order cancellation rate are as below:</p>

<ul>
<li>1. Set orders’ price to BBO prices as close as possible;</li>
<li>2. Prolong the interval properly between each order placement and cancellation;</li>
<li>3. Try to increase your amount for each order and reduce the frequency of order;</li>
<li>4. Try to improve your order fulfillment rate:</li>
<li>（1）Please try to use order prices types that help more on order fulfillment in preference such as BBO, Optimal 5, Optimal 10, Optimal 20, lightning Close, opponent_ioc, lightning_ioc, optimal_5_ioc, optimal_10_ioc，optimal_20_ioc，opponent_fok，lightning_fok，optimal_5_fok，optimal_10_fok，optimal_20_fok, etc.</li>
<li>（2）Try to use best bid/ask price when placing IOC orders, FOK orders and Post_only orders.</li>
<li>5. Please try to extend your request polling cycle when implementing your strategy.</li>
</ul></li>
</ul>
<h2 id="maintenance-with-service-suspended">Maintenance with service suspended</h2>
<p>During the maintenance of the business system, in addition to the below two interfaces(<a href="https://docs.huobigroup.com/docs/coin_margined_swap/v1/en/#get-system-status">Get system status</a>, <a href="https://docs.huobigroup.com/docs/coin_margined_swap/v1/en/#query-whether-the-system-is-available">Query whether the system is available</a>) for users to query the system status, all “rest” interfaces of the API business will return this in a fixed manner:<code>{"status": "maintain"}</code>. During maintenance with service suspended，all websocket notify interfaces except subscribing system status updates（<a href="https://docs.huobigroup.com/docs/coin_margined_swap/v1/en/#subscribe-system-status-updates">Subscribe system status updates</a>）can't work，and will push 1006 error code to clients.</p>

<blockquote>
<p>Response</p>
</blockquote>
<pre class="highlight json tab-json"><code><span class="p">{</span><span class="w">
    </span><span class="s2">"status"</span><span class="p">:</span><span class="w"> </span><span class="s2">"maintain"</span><span class="w">
</span><span class="p">}</span><span class="w">
</span></code></pre><h3 id="the-two-interfaces-are">The two interfaces are:</h3>
<ul>
<li>Get system status: https://status-swap.huobigroup.com/api/v2/summary.json</li>
<li>Query whether the system is available: https://api.hbdm.com/heartbeat/</li>
</ul>

<p>Besides the above two rest interfaces, for getting the infomation that system maintenance with service suspended, could by subscrib system status updates websocket interface.</p>
<h2 id="get-system-status">Get system status</h2>
<p>This endpoint allows users to get system status, Incidents and planned maintenance.</p>

<p>The system status can also be obtained through email, SMS, webhook, RSS/Atom feed. Users can You can click <a href="https://status-swap.huobigroup.com/">here</a> to subscribe. The subscription function depends on Google services. Before you subscribe, please ensure that you can access Google services normally. </p>
<pre class="highlight shell tab-shell" style=""><code>curl <span class="s2">"https://status-swap.huobigroup.com/api/v2/summary.json"</span>
</code></pre><h3 id="http-request">HTTP Request</h3>
<ul>
<li>GET <code>https://status-swap.huobigroup.com/api/v2/summary.json</code></li>
</ul>
<h3 id="request-parameters">Request Parameters</h3>
<p>No parameter is available for this endpoint.</p>

<blockquote>
<p>Response:</p>
</blockquote>
<pre class="highlight json tab-json"><code><span class="p">{</span><span class="w">
  </span><span class="s2">"page"</span><span class="p">:</span><span class="w"> </span><span class="p">{</span><span class="w">  </span><span class="err">//</span><span class="w"> </span><span class="err">Basic</span><span class="w"> </span><span class="err">information</span><span class="w"> </span><span class="err">of</span><span class="w"> </span><span class="err">status</span><span class="w"> </span><span class="err">page</span><span class="w">
    </span><span class="s2">"id"</span><span class="p">:</span><span class="w"> </span><span class="s2">"p0qjfl24znv5"</span><span class="p">,</span><span class="w">  </span><span class="err">//</span><span class="w"> </span><span class="err">page</span><span class="w"> </span><span class="err">id</span><span class="w">
    </span><span class="s2">"name"</span><span class="p">:</span><span class="w"> </span><span class="s2">"Huobi"</span><span class="p">,</span><span class="w">  </span><span class="err">//</span><span class="w"> </span><span class="err">page</span><span class="w"> </span><span class="err">name</span><span class="w">
    </span><span class="s2">"url"</span><span class="p">:</span><span class="w"> </span><span class="s2">"https://status-swap.huobigroup.com/"</span><span class="p">,</span><span class="w"> </span><span class="err">//</span><span class="w"> </span><span class="err">page</span><span class="w"> </span><span class="err">url</span><span class="w">
    </span><span class="s2">"time_zone"</span><span class="p">:</span><span class="w"> </span><span class="s2">"Etc/UTC"</span><span class="p">,</span><span class="w"> </span><span class="err">//</span><span class="w"> </span><span class="err">time</span><span class="w"> </span><span class="err">zone</span><span class="w">
    </span><span class="s2">"updated_at"</span><span class="p">:</span><span class="w"> </span><span class="s2">"2020-02-07T10:25:14.717Z"</span><span class="w"> </span><span class="err">//</span><span class="w"> </span><span class="err">page</span><span class="w"> </span><span class="err">update</span><span class="w"> </span><span class="err">time</span><span class="w">
  </span><span class="p">},</span><span class="w">
  </span><span class="s2">"components"</span><span class="p">:</span><span class="w"> </span><span class="p">[</span><span class="w">  </span><span class="err">//</span><span class="w"> </span><span class="err">System</span><span class="w"> </span><span class="err">components</span><span class="w"> </span><span class="err">and</span><span class="w"> </span><span class="err">their</span><span class="w"> </span><span class="err">status</span><span class="w">
    </span><span class="p">{</span><span class="w">
      </span><span class="s2">"id"</span><span class="p">:</span><span class="w"> </span><span class="s2">"h028tnzw1n5l"</span><span class="p">,</span><span class="w">  </span><span class="err">//</span><span class="w"> </span><span class="err">component</span><span class="w"> </span><span class="err">id</span><span class="w">
      </span><span class="s2">"name"</span><span class="p">:</span><span class="w"> </span><span class="s2">"Deposit"</span><span class="p">,</span><span class="w"> </span><span class="err">//</span><span class="w"> </span><span class="err">component</span><span class="w"> </span><span class="err">name</span><span class="w">
      </span><span class="s2">"status"</span><span class="p">:</span><span class="w"> </span><span class="s2">"operational"</span><span class="p">,</span><span class="w"> </span><span class="err">//</span><span class="w"> </span><span class="err">component</span><span class="w"> </span><span class="err">status</span><span class="w">
      </span><span class="s2">"created_at"</span><span class="p">:</span><span class="w"> </span><span class="s2">"2019-12-05T02:07:12.372Z"</span><span class="p">,</span><span class="w">  </span><span class="err">//</span><span class="w"> </span><span class="err">component</span><span class="w"> </span><span class="err">create</span><span class="w"> </span><span class="err">time</span><span class="w">
      </span><span class="s2">"updated_at"</span><span class="p">:</span><span class="w"> </span><span class="s2">"2020-02-07T09:27:15.563Z"</span><span class="p">,</span><span class="w"> </span><span class="err">//</span><span class="w"> </span><span class="err">component</span><span class="w"> </span><span class="err">update</span><span class="w"> </span><span class="err">time</span><span class="w">
      </span><span class="s2">"position"</span><span class="p">:</span><span class="w"> </span><span class="mi">1</span><span class="p">,</span><span class="w">
      </span><span class="s2">"description"</span><span class="p">:</span><span class="w"> </span><span class="kc">null</span><span class="p">,</span><span class="w">
      </span><span class="s2">"showcase"</span><span class="p">:</span><span class="w"> </span><span class="kc">true</span><span class="p">,</span><span class="w">
      </span><span class="s2">"group_id"</span><span class="p">:</span><span class="w"> </span><span class="s2">"gtd0nyr3pf0k"</span><span class="p">,</span><span class="w">  
      </span><span class="s2">"page_id"</span><span class="p">:</span><span class="w"> </span><span class="s2">"p0qjfl24znv5"</span><span class="p">,</span><span class="w"> 
      </span><span class="s2">"group"</span><span class="p">:</span><span class="w"> </span><span class="kc">false</span><span class="p">,</span><span class="w">
      </span><span class="s2">"only_show_if_degraded"</span><span class="p">:</span><span class="w"> </span><span class="kc">false</span><span class="w">
    </span><span class="p">}</span><span class="w">
  </span><span class="p">],</span><span class="w">
  </span><span class="s2">"incidents"</span><span class="p">:</span><span class="w"> </span><span class="p">[</span><span class="w"> </span><span class="err">//</span><span class="w"> </span><span class="err">System</span><span class="w"> </span><span class="err">fault</span><span class="w"> </span><span class="err">incidents</span><span class="w"> </span><span class="err">and</span><span class="w"> </span><span class="err">their</span><span class="w"> </span><span class="err">status</span><span class="w">
        </span><span class="p">{</span><span class="w">
            </span><span class="s2">"id"</span><span class="p">:</span><span class="w"> </span><span class="s2">"rclfxz2g21ly"</span><span class="p">,</span><span class="w">  </span><span class="err">//</span><span class="w"> </span><span class="err">incident</span><span class="w"> </span><span class="err">id</span><span class="w">
            </span><span class="s2">"name"</span><span class="p">:</span><span class="w"> </span><span class="s2">"Market data is delayed"</span><span class="p">,</span><span class="w">  </span><span class="err">//</span><span class="w"> </span><span class="err">incident</span><span class="w"> </span><span class="err">name</span><span class="w">
            </span><span class="s2">"status"</span><span class="p">:</span><span class="w"> </span><span class="s2">"investigating"</span><span class="p">,</span><span class="w">  </span><span class="err">//</span><span class="w"> </span><span class="err">incident</span><span class="w"> </span><span class="err">stutus</span><span class="w">
            </span><span class="s2">"created_at"</span><span class="p">:</span><span class="w"> </span><span class="s2">"2020-02-11T03:15:01.913Z"</span><span class="p">,</span><span class="w">  </span><span class="err">//</span><span class="w"> </span><span class="err">incident</span><span class="w"> </span><span class="err">create</span><span class="w"> </span><span class="err">time</span><span class="w">
            </span><span class="s2">"updated_at"</span><span class="p">:</span><span class="w"> </span><span class="s2">"2020-02-11T03:15:02.003Z"</span><span class="p">,</span><span class="w">   </span><span class="err">//</span><span class="w"> </span><span class="err">incident</span><span class="w"> </span><span class="err">update</span><span class="w"> </span><span class="err">time</span><span class="w">
            </span><span class="s2">"monitoring_at"</span><span class="p">:</span><span class="w"> </span><span class="kc">null</span><span class="p">,</span><span class="w">
            </span><span class="s2">"resolved_at"</span><span class="p">:</span><span class="w"> </span><span class="kc">null</span><span class="p">,</span><span class="w">
            </span><span class="s2">"impact"</span><span class="p">:</span><span class="w"> </span><span class="s2">"minor"</span><span class="p">,</span><span class="w">  </span><span class="err">//</span><span class="w"> </span><span class="err">incident</span><span class="w"> </span><span class="err">impact</span><span class="w">
            </span><span class="s2">"shortlink"</span><span class="p">:</span><span class="w"> </span><span class="s2">"http://stspg.io/pkvbwp8jppf9"</span><span class="p">,</span><span class="w">
            </span><span class="s2">"started_at"</span><span class="p">:</span><span class="w"> </span><span class="s2">"2020-02-11T03:15:01.906Z"</span><span class="p">,</span><span class="w">
            </span><span class="s2">"page_id"</span><span class="p">:</span><span class="w"> </span><span class="s2">"p0qjfl24znv5"</span><span class="p">,</span><span class="w">
            </span><span class="s2">"incident_updates"</span><span class="p">:</span><span class="w"> </span><span class="p">[</span><span class="w"> 
                </span><span class="p">{</span><span class="w">
                    </span><span class="s2">"id"</span><span class="p">:</span><span class="w"> </span><span class="s2">"dwfsk5ttyvtb"</span><span class="p">,</span><span class="w">   
                    </span><span class="s2">"status"</span><span class="p">:</span><span class="w"> </span><span class="s2">"investigating"</span><span class="p">,</span><span class="w">   
                    </span><span class="s2">"body"</span><span class="p">:</span><span class="w"> </span><span class="s2">"Market data is delayed"</span><span class="p">,</span><span class="w"> 
                    </span><span class="s2">"incident_id"</span><span class="p">:</span><span class="w"> </span><span class="s2">"rclfxz2g21ly"</span><span class="p">,</span><span class="w">   
                    </span><span class="s2">"created_at"</span><span class="p">:</span><span class="w"> </span><span class="s2">"2020-02-11T03:15:02.000Z"</span><span class="p">,</span><span class="w">    
                    </span><span class="s2">"updated_at"</span><span class="p">:</span><span class="w"> </span><span class="s2">"2020-02-11T03:15:02.000Z"</span><span class="p">,</span><span class="w">  
                    </span><span class="s2">"display_at"</span><span class="p">:</span><span class="w"> </span><span class="s2">"2020-02-11T03:15:02.000Z"</span><span class="p">,</span><span class="w">   
                    </span><span class="s2">"affected_components"</span><span class="p">:</span><span class="w"> </span><span class="p">[</span><span class="w">  
                        </span><span class="p">{</span><span class="w">
                            </span><span class="s2">"code"</span><span class="p">:</span><span class="w"> </span><span class="s2">"nctwm9tghxh6"</span><span class="p">,</span><span class="w">  
                            </span><span class="s2">"name"</span><span class="p">:</span><span class="w"> </span><span class="s2">"Market data"</span><span class="p">,</span><span class="w">  
                            </span><span class="s2">"old_status"</span><span class="p">:</span><span class="w"> </span><span class="s2">"operational"</span><span class="p">,</span><span class="w">  
                            </span><span class="s2">"new_status"</span><span class="p">:</span><span class="w"> </span><span class="s2">"degraded_performance"</span><span class="w">  
                        </span><span class="p">}</span><span class="w">
                    </span><span class="p">],</span><span class="w">
                    </span><span class="s2">"deliver_notifications"</span><span class="p">:</span><span class="w"> </span><span class="kc">true</span><span class="p">,</span><span class="w">
                    </span><span class="s2">"custom_tweet"</span><span class="p">:</span><span class="w"> </span><span class="kc">null</span><span class="p">,</span><span class="w">
                    </span><span class="s2">"tweet_id"</span><span class="p">:</span><span class="w"> </span><span class="kc">null</span><span class="w">
                </span><span class="p">}</span><span class="w">
            </span><span class="p">],</span><span class="w">
            </span><span class="s2">"components"</span><span class="p">:</span><span class="w"> </span><span class="p">[</span><span class="w">  
                </span><span class="p">{</span><span class="w">
                    </span><span class="s2">"id"</span><span class="p">:</span><span class="w"> </span><span class="s2">"nctwm9tghxh6"</span><span class="p">,</span><span class="w">   
                    </span><span class="s2">"name"</span><span class="p">:</span><span class="w"> </span><span class="s2">"Market data"</span><span class="p">,</span><span class="w">  
                    </span><span class="s2">"status"</span><span class="p">:</span><span class="w"> </span><span class="s2">"degraded_performance"</span><span class="p">,</span><span class="w"> 
                    </span><span class="s2">"created_at"</span><span class="p">:</span><span class="w"> </span><span class="s2">"2020-01-13T09:34:48.284Z"</span><span class="p">,</span><span class="w"> 
                    </span><span class="s2">"updated_at"</span><span class="p">:</span><span class="w"> </span><span class="s2">"2020-02-11T03:15:01.951Z"</span><span class="p">,</span><span class="w"> 
                    </span><span class="s2">"position"</span><span class="p">:</span><span class="w"> </span><span class="mi">8</span><span class="p">,</span><span class="w">
                    </span><span class="s2">"description"</span><span class="p">:</span><span class="w"> </span><span class="kc">null</span><span class="p">,</span><span class="w">
                    </span><span class="s2">"showcase"</span><span class="p">:</span><span class="w"> </span><span class="kc">false</span><span class="p">,</span><span class="w">
                    </span><span class="s2">"group_id"</span><span class="p">:</span><span class="w"> </span><span class="kc">null</span><span class="p">,</span><span class="w">
                    </span><span class="s2">"page_id"</span><span class="p">:</span><span class="w"> </span><span class="s2">"p0qjfl24znv5"</span><span class="p">,</span><span class="w">
                    </span><span class="s2">"group"</span><span class="p">:</span><span class="w"> </span><span class="kc">false</span><span class="p">,</span><span class="w">
                    </span><span class="s2">"only_show_if_degraded"</span><span class="p">:</span><span class="w"> </span><span class="kc">false</span><span class="w">
                </span><span class="p">}</span><span class="w">
            </span><span class="p">]</span><span class="w">
        </span><span class="p">}</span><span class="w">
    </span><span class="p">],</span><span class="w">
      </span><span class="s2">"scheduled_maintenances"</span><span class="p">:</span><span class="w"> </span><span class="p">[</span><span class="w">  </span><span class="err">//</span><span class="w"> </span><span class="err">System</span><span class="w"> </span><span class="err">scheduled</span><span class="w"> </span><span class="err">maintenance</span><span class="w"> </span><span class="err">events</span><span class="w"> </span><span class="err">and</span><span class="w"> </span><span class="err">their</span><span class="w"> </span><span class="err">status</span><span class="w">
        </span><span class="p">{</span><span class="w">
            </span><span class="s2">"id"</span><span class="p">:</span><span class="w"> </span><span class="s2">"k7g299zl765l"</span><span class="p">,</span><span class="w"> </span><span class="err">//</span><span class="w"> </span><span class="err">incident</span><span class="w"> </span><span class="err">id</span><span class="w">
            </span><span class="s2">"name"</span><span class="p">:</span><span class="w"> </span><span class="s2">"Schedule maintenance"</span><span class="p">,</span><span class="w"> </span><span class="err">//</span><span class="w"> </span><span class="err">incident</span><span class="w"> </span><span class="err">name</span><span class="w">
            </span><span class="s2">"status"</span><span class="p">:</span><span class="w"> </span><span class="s2">"scheduled"</span><span class="p">,</span><span class="w"> </span><span class="err">//</span><span class="w"> </span><span class="err">incident</span><span class="w"> </span><span class="err">status</span><span class="w">
            </span><span class="s2">"created_at"</span><span class="p">:</span><span class="w"> </span><span class="s2">"2020-02-11T03:16:31.481Z"</span><span class="p">,</span><span class="w">  </span><span class="err">//</span><span class="w"> </span><span class="err">incident</span><span class="w"> </span><span class="err">create</span><span class="w"> </span><span class="err">time</span><span class="w">
            </span><span class="s2">"updated_at"</span><span class="p">:</span><span class="w"> </span><span class="s2">"2020-02-11T03:16:31.530Z"</span><span class="p">,</span><span class="w">  </span><span class="err">//</span><span class="w"> </span><span class="err">incident</span><span class="w"> </span><span class="err">update</span><span class="w"> </span><span class="err">time</span><span class="w">
            </span><span class="s2">"monitoring_at"</span><span class="p">:</span><span class="w"> </span><span class="kc">null</span><span class="p">,</span><span class="w">
            </span><span class="s2">"resolved_at"</span><span class="p">:</span><span class="w"> </span><span class="kc">null</span><span class="p">,</span><span class="w">
            </span><span class="s2">"impact"</span><span class="p">:</span><span class="w"> </span><span class="s2">"maintenance"</span><span class="p">,</span><span class="w">  </span><span class="err">//</span><span class="w"> </span><span class="err">incident</span><span class="w"> </span><span class="err">impact</span><span class="w">
            </span><span class="s2">"shortlink"</span><span class="p">:</span><span class="w"> </span><span class="s2">"http://stspg.io/md4t4ym7nytd"</span><span class="p">,</span><span class="w">
            </span><span class="s2">"started_at"</span><span class="p">:</span><span class="w"> </span><span class="s2">"2020-02-11T03:16:31.474Z"</span><span class="p">,</span><span class="w">
            </span><span class="s2">"page_id"</span><span class="p">:</span><span class="w"> </span><span class="s2">"p0qjfl24znv5"</span><span class="p">,</span><span class="w">
            </span><span class="s2">"incident_updates"</span><span class="p">:</span><span class="w"> </span><span class="p">[</span><span class="w">  
                </span><span class="p">{</span><span class="w">
                    </span><span class="s2">"id"</span><span class="p">:</span><span class="w"> </span><span class="s2">"8whgr3rlbld8"</span><span class="p">,</span><span class="w">  
                    </span><span class="s2">"status"</span><span class="p">:</span><span class="w"> </span><span class="s2">"scheduled"</span><span class="p">,</span><span class="w"> 
                    </span><span class="s2">"body"</span><span class="p">:</span><span class="w"> </span><span class="s2">"We will be undergoing scheduled maintenance during this time."</span><span class="p">,</span><span class="w"> 
                    </span><span class="s2">"incident_id"</span><span class="p">:</span><span class="w"> </span><span class="s2">"k7g299zl765l"</span><span class="p">,</span><span class="w">  
                    </span><span class="s2">"created_at"</span><span class="p">:</span><span class="w"> </span><span class="s2">"2020-02-11T03:16:31.527Z"</span><span class="p">,</span><span class="w">  
                    </span><span class="s2">"updated_at"</span><span class="p">:</span><span class="w"> </span><span class="s2">"2020-02-11T03:16:31.527Z"</span><span class="p">,</span><span class="w">  
                    </span><span class="s2">"display_at"</span><span class="p">:</span><span class="w"> </span><span class="s2">"2020-02-11T03:16:31.527Z"</span><span class="p">,</span><span class="w">  
                    </span><span class="s2">"affected_components"</span><span class="p">:</span><span class="w"> </span><span class="p">[</span><span class="w">  
                        </span><span class="p">{</span><span class="w">
                            </span><span class="s2">"code"</span><span class="p">:</span><span class="w"> </span><span class="s2">"h028tnzw1n5l"</span><span class="p">,</span><span class="w">  
                            </span><span class="s2">"name"</span><span class="p">:</span><span class="w"> </span><span class="s2">"Deposit And Withdraw - Deposit"</span><span class="p">,</span><span class="w">  
                            </span><span class="s2">"old_status"</span><span class="p">:</span><span class="w"> </span><span class="s2">"operational"</span><span class="p">,</span><span class="w">  
                            </span><span class="s2">"new_status"</span><span class="p">:</span><span class="w"> </span><span class="s2">"operational"</span><span class="w"> 
                        </span><span class="p">}</span><span class="w">
                    </span><span class="p">],</span><span class="w">
                    </span><span class="s2">"deliver_notifications"</span><span class="p">:</span><span class="w"> </span><span class="kc">true</span><span class="p">,</span><span class="w">
                    </span><span class="s2">"custom_tweet"</span><span class="p">:</span><span class="w"> </span><span class="kc">null</span><span class="p">,</span><span class="w">
                    </span><span class="s2">"tweet_id"</span><span class="p">:</span><span class="w"> </span><span class="kc">null</span><span class="w">
                </span><span class="p">}</span><span class="w">
            </span><span class="p">],</span><span class="w">
            </span><span class="s2">"components"</span><span class="p">:</span><span class="w"> </span><span class="p">[</span><span class="w">  
                </span><span class="p">{</span><span class="w">
                    </span><span class="s2">"id"</span><span class="p">:</span><span class="w"> </span><span class="s2">"h028tnzw1n5l"</span><span class="p">,</span><span class="w">  
                    </span><span class="s2">"name"</span><span class="p">:</span><span class="w"> </span><span class="s2">"Deposit"</span><span class="p">,</span><span class="w"> 
                    </span><span class="s2">"status"</span><span class="p">:</span><span class="w"> </span><span class="s2">"operational"</span><span class="p">,</span><span class="w"> 
                    </span><span class="s2">"created_at"</span><span class="p">:</span><span class="w"> </span><span class="s2">"2019-12-05T02:07:12.372Z"</span><span class="p">,</span><span class="w">  
                    </span><span class="s2">"updated_at"</span><span class="p">:</span><span class="w"> </span><span class="s2">"2020-02-10T12:34:52.970Z"</span><span class="p">,</span><span class="w">  
                    </span><span class="s2">"position"</span><span class="p">:</span><span class="w"> </span><span class="mi">1</span><span class="p">,</span><span class="w">
                    </span><span class="s2">"description"</span><span class="p">:</span><span class="w"> </span><span class="kc">null</span><span class="p">,</span><span class="w">
                    </span><span class="s2">"showcase"</span><span class="p">:</span><span class="w"> </span><span class="kc">false</span><span class="p">,</span><span class="w">
                    </span><span class="s2">"group_id"</span><span class="p">:</span><span class="w"> </span><span class="s2">"gtd0nyr3pf0k"</span><span class="p">,</span><span class="w">
                    </span><span class="s2">"page_id"</span><span class="p">:</span><span class="w"> </span><span class="s2">"p0qjfl24znv5"</span><span class="p">,</span><span class="w">
                    </span><span class="s2">"group"</span><span class="p">:</span><span class="w"> </span><span class="kc">false</span><span class="p">,</span><span class="w">
                    </span><span class="s2">"only_show_if_degraded"</span><span class="p">:</span><span class="w"> </span><span class="kc">false</span><span class="w">
                </span><span class="p">}</span><span class="w">
            </span><span class="p">],</span><span class="w">
            </span><span class="s2">"scheduled_for"</span><span class="p">:</span><span class="w"> </span><span class="s2">"2020-02-15T00:00:00.000Z"</span><span class="p">,</span><span class="w">  </span><span class="err">//</span><span class="w"> </span><span class="err">scheduled</span><span class="w"> </span><span class="err">maintenance</span><span class="w"> </span><span class="err">start</span><span class="w"> </span><span class="err">time</span><span class="w">
            </span><span class="s2">"scheduled_until"</span><span class="p">:</span><span class="w"> </span><span class="s2">"2020-02-15T01:00:00.000Z"</span><span class="w">  </span><span class="err">//</span><span class="w"> </span><span class="err">scheduled</span><span class="w"> </span><span class="err">maintenance</span><span class="w"> </span><span class="err">end</span><span class="w"> </span><span class="err">time</span><span class="w">
        </span><span class="p">}</span><span class="w">
    </span><span class="p">],</span><span class="w">
    </span><span class="s2">"status"</span><span class="p">:</span><span class="w"> </span><span class="p">{</span><span class="w">  </span><span class="err">//</span><span class="w"> </span><span class="err">The</span><span class="w"> </span><span class="err">overall</span><span class="w"> </span><span class="err">current</span><span class="w"> </span><span class="err">status</span><span class="w"> </span><span class="err">of</span><span class="w"> </span><span class="err">the</span><span class="w"> </span><span class="err">system</span><span class="w">
        </span><span class="s2">"indicator"</span><span class="p">:</span><span class="w"> </span><span class="s2">"minor"</span><span class="p">,</span><span class="w">   </span><span class="err">//</span><span class="w"> </span><span class="err">system</span><span class="w"> </span><span class="err">indicator</span><span class="w">
        </span><span class="s2">"description"</span><span class="p">:</span><span class="w"> </span><span class="s2">"Partially Degraded Service"</span><span class="w">  </span><span class="err">//</span><span class="w"> </span><span class="err">system</span><span class="w"> </span><span class="err">description</span><span class="w">
    </span><span class="p">}</span><span class="w">
</span><span class="p">}</span><span class="w">
</span></code></pre><h3 id="response-content">Response Content</h3>
<table><thead>
<tr>
<th>Field</th>
<th>Data Type</th>
<th>Description</th>
</tr>
</thead><tbody>
<tr>
<td>page</td>
<td></td>
<td>basic information of status page</td>
</tr>
<tr>
<td>{id</td>
<td>string</td>
<td>page id</td>
</tr>
<tr>
<td>name</td>
<td>string</td>
<td>page name</td>
</tr>
<tr>
<td>url</td>
<td>string</td>
<td>page url</td>
</tr>
<tr>
<td>time_zone</td>
<td>string</td>
<td>time zone</td>
</tr>
<tr>
<td>updated_at}</td>
<td>string</td>
<td>page update time</td>
</tr>
<tr>
<td>components</td>
<td></td>
<td>System components and their status</td>
</tr>
<tr>
<td>[{id</td>
<td>string</td>
<td>component id</td>
</tr>
<tr>
<td>name</td>
<td>string</td>
<td>component name, including Order submission, Order cancellation, Deposit etc.</td>
</tr>
<tr>
<td>status</td>
<td>string</td>
<td>component status, value range: operational, degraded_performance, partial_outage, major_outage, under maintenance</td>
</tr>
<tr>
<td>created_at</td>
<td>string</td>
<td>component create time</td>
</tr>
<tr>
<td>updated_at</td>
<td>string</td>
<td>component update time</td>
</tr>
<tr>
<td>.......}]</td>
<td></td>
<td>for details of other fields, please refer to the return example</td>
</tr>
<tr>
<td>incidents</td>
<td></td>
<td>System fault incident and their status. If there is no fault at present, it will return to null</td>
</tr>
<tr>
<td>[{id</td>
<td>string</td>
<td>incident id</td>
</tr>
<tr>
<td>name</td>
<td>string</td>
<td>incident name</td>
</tr>
<tr>
<td>status</td>
<td>string</td>
<td>incident staus, value range: investigating, identified, monitoring, resolved</td>
</tr>
<tr>
<td>created_at</td>
<td>string</td>
<td>incident creat time</td>
</tr>
<tr>
<td>updated_at</td>
<td>string</td>
<td>incident update time</td>
</tr>
<tr>
<td>.......}]</td>
<td></td>
<td>for details of other fields, please refer to the return example</td>
</tr>
<tr>
<td>scheduled_maintenances</td>
<td></td>
<td>System scheduled maintenance incident and status. If there is no scheduled maintenance at present, it will return to null</td>
</tr>
<tr>
<td>[{id</td>
<td>string</td>
<td>incident id</td>
</tr>
<tr>
<td>name</td>
<td>string</td>
<td>incident name</td>
</tr>
<tr>
<td>status</td>
<td>string</td>
<td>incident staus, value range: scheduled, in progress, verifying, completed</td>
</tr>
<tr>
<td>created_at</td>
<td>string</td>
<td>incident creat time</td>
</tr>
<tr>
<td>updated_at</td>
<td>string</td>
<td>incident update time</td>
</tr>
<tr>
<td>scheduled_for</td>
<td>string</td>
<td>scheduled maintenance start time</td>
</tr>
<tr>
<td>scheduled_until</td>
<td>string</td>
<td>scheduled maintenance end time</td>
</tr>
<tr>
<td>.......}]</td>
<td></td>
<td>for details of other fields, please refer to the return example</td>
</tr>
<tr>
<td>status</td>
<td></td>
<td>The overall current status of the system</td>
</tr>
<tr>
<td>{indicator</td>
<td>string</td>
<td>system indicator, value range: none, minor, major, critical, maintenance</td>
</tr>
<tr>
<td>description}</td>
<td>string</td>
<td>system description, value range: All Systems Operational, Minor Service Outager, Partial System Outage, Partially Degraded Service, Service Under Maintenance</td>
</tr>
</tbody></table>
<h2 id="query-whether-the-system-is-available">Query whether the system is available</h2>
<ul>
<li>Interface <code>https://api.hbdm.com/heartbeat/</code></li>
</ul>
<h3 id="returning-parameter">Returning Parameter</h3>
<table><thead>
<tr>
<th>Parameter Name</th>
<th>Parameter Type</th>
<th>Desc</th>
</tr>
</thead><tbody>
<tr>
<td>status</td>
<td>string</td>
<td>"ok" or "error"...</td>
</tr>
<tr>
<td>&lt;data&gt;</td>
<td>dict object</td>
<td></td>
</tr>
<tr>
<td>heartbeat</td>
<td>int</td>
<td>future 1: avaiable 0: not available(maintenance with service suspended)</td>
</tr>
<tr>
<td>swap_heartbeat</td>
<td>int</td>
<td>coin margined swap 1: avaiable 0: not available(maintenance with service suspended)</td>
</tr>
<tr>
<td>estimated_recovery_time</td>
<td>long</td>
<td>null: normal. estimated recovery time :millionseconds.</td>
</tr>
<tr>
<td>swap_estimated_recovery_time</td>
<td>long</td>
<td>null: normal. coin margined swap estimated recovery time millionseconds.</td>
</tr>
<tr>
<td>option_heartbeat</td>
<td>int</td>
<td>option 1: avaiable 0: not available(maintenance with service suspended)</td>
</tr>
<tr>
<td>option_estimated_recovery_time</td>
<td>long</td>
<td>null: normal. option estimated recovery time :millionseconds.</td>
</tr>
<tr>
<td>linear_swap_heartbeat</td>
<td>long</td>
<td>USDT margined swap 1: avaiable 0: not available(maintenance with service suspended)</td>
</tr>
<tr>
<td>linear_swap_estimated_recovery_time</td>
<td>long</td>
<td>null: normal. USDT margined swap estimated recovery time millionseconds.</td>
</tr>
<tr>
<td>&lt;/data&gt;</td>
<td></td>
<td></td>
</tr>
</tbody></table>

<blockquote>
<p>Response:</p>
</blockquote>
<pre class="highlight json tab-json"><code><span class="w">
</span><span class="p">{</span><span class="w">
    </span><span class="s2">"status"</span><span class="p">:</span><span class="s2">"ok"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"data"</span><span class="p">:{</span><span class="w">
        </span><span class="s2">"heartbeat"</span><span class="p">:</span><span class="mi">1</span><span class="p">,</span><span class="w">
        </span><span class="s2">"estimated_recovery_time"</span><span class="p">:</span><span class="kc">null</span><span class="p">,</span><span class="w">
        </span><span class="s2">"swap_heartbeat"</span><span class="p">:</span><span class="mi">1</span><span class="p">,</span><span class="w">
        </span><span class="s2">"swap_estimated_recovery_time"</span><span class="p">:</span><span class="kc">null</span><span class="p">,</span><span class="w">
        </span><span class="s2">"option_heartbeat"</span><span class="p">:</span><span class="mi">1</span><span class="p">,</span><span class="w">
        </span><span class="s2">"option_estimated_recovery_time"</span><span class="p">:</span><span class="kc">null</span><span class="p">,</span><span class="w">
        </span><span class="s2">"linear_swap_heartbeat"</span><span class="p">:</span><span class="mi">1</span><span class="p">,</span><span class="w">
        </span><span class="s2">"linear_swap_estimated_recovery_time"</span><span class="p">:</span><span class="kc">null</span><span class="w">
    </span><span class="p">},</span><span class="w">
    </span><span class="s2">"ts"</span><span class="p">:</span><span class="mi">1557714418033</span><span class="w">
</span><span class="p">}</span><span class="w">
</span></code></pre>
<ul>
<li>Notice: Heartbeat is 1 is available, 0 is not available. </li>
</ul>
<h2 id="get-current-system-timestamp">Get current system timestamp</h2>
<p>get <code>https://api.hbdm.com/api/v1/timestamp</code></p>
<h3 id="request">request</h3>
<p>null</p>

<blockquote>
<p>response</p>
</blockquote>
<pre class="highlight json tab-json"><code><span class="w">
</span><span class="p">{</span><span class="w">
    </span><span class="s2">"status"</span><span class="p">:</span><span class="w"> </span><span class="s2">"ok"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"ts"</span><span class="p">:</span><span class="w"> </span><span class="mi">1578124684692</span><span class="w">
</span><span class="p">}</span><span class="w">

</span></code></pre><h3 id="returning-parameter-2">Returning Parameter</h3>
<table><thead>
<tr>
<th>Parameter Name</th>
<th>Mandatory</th>
<th>Type</th>
<th>Desc</th>
<th>Value Range</th>
</tr>
</thead><tbody>
<tr>
<td>status</td>
<td>true</td>
<td>string</td>
<td>Request Processing Result</td>
<td></td>
</tr>
<tr>
<td>ts</td>
<td>true</td>
<td>long</td>
<td>current system timestamp</td>
<td></td>
</tr>
</tbody></table>
<h4 id="note">Note:</h4>
<ul>
<li>It can be used for  system time calibration.</li>
</ul>
<h2 id="details-of-each-error-code">Details of Each Error Code</h2>
<table><thead>
<tr>
<th>Error Code</th>
<th>Error Details Description</th>
</tr>
</thead><tbody>
<tr>
<td>403</td>
<td>invalid ID</td>
</tr>
<tr>
<td>1000</td>
<td>System error.</td>
</tr>
<tr>
<td>1001</td>
<td>System is unprepared.</td>
</tr>
<tr>
<td>1002</td>
<td>Query error.</td>
</tr>
<tr>
<td>1003</td>
<td>Abnormal redis operation.</td>
</tr>
<tr>
<td>1004</td>
<td>System busy. Please try again later.</td>
</tr>
<tr>
<td>1010</td>
<td>Account doesn't exist.</td>
</tr>
<tr>
<td>1011</td>
<td>The user's session doesn't exist.</td>
</tr>
<tr>
<td>1012</td>
<td>The user's account doesn't exist.</td>
</tr>
<tr>
<td>1013</td>
<td>This contract symbol doesn't exist.</td>
</tr>
<tr>
<td>1014</td>
<td>This contract doesn't exist.</td>
</tr>
<tr>
<td>1015</td>
<td>The index price does not exist.</td>
</tr>
<tr>
<td>1016</td>
<td>The bid offer does not exist. Please input the price.</td>
</tr>
<tr>
<td>1017</td>
<td>Order doesn't exist.</td>
</tr>
<tr>
<td>1018</td>
<td>Main account doesn't exist.</td>
</tr>
<tr>
<td>1019</td>
<td>Main account doesn't exist in the sub-account white list.</td>
</tr>
<tr>
<td>1020</td>
<td>The number of your sub-account exceeds the maximum. Please contact customer service.</td>
</tr>
<tr>
<td>1021</td>
<td>Account open failed. Main account hasn’t opened contract trading account yet.</td>
</tr>
<tr>
<td>1030</td>
<td>Input error.</td>
</tr>
<tr>
<td>1031</td>
<td>Incorrect form source.</td>
</tr>
<tr>
<td>1032</td>
<td>The number of access exceeded the limit.</td>
</tr>
<tr>
<td>1033</td>
<td>Incorrect field of contract period.</td>
</tr>
<tr>
<td>1034</td>
<td>Incorrect field of order price type.</td>
</tr>
<tr>
<td>1035</td>
<td>Incorrect field of form direction.</td>
</tr>
<tr>
<td>1036</td>
<td>Incorrect field of open long form.</td>
</tr>
<tr>
<td>1037</td>
<td>The leverage is invalid. Please contact the customer service.</td>
</tr>
<tr>
<td>1038</td>
<td>The order price exceeds the precision limit, please modify and order again.</td>
</tr>
<tr>
<td>1039</td>
<td>Buy price must be lower than {0}{1}. Sell price must exceed {2}{3}.</td>
</tr>
<tr>
<td>1040</td>
<td>Invalid amount, please modify and order again.</td>
</tr>
<tr>
<td>1041</td>
<td>The order amount exceeds the limit ({0}Cont), please modify and order again.</td>
</tr>
<tr>
<td>1042</td>
<td>Current positions have triggered position limits ({0}Cont). Please order after changing the amount.</td>
</tr>
<tr>
<td>1043</td>
<td>Current positions have triggered position limits ({0}Cont). Please order after changing the amount.</td>
</tr>
<tr>
<td>1044</td>
<td>Current positions have triggered position limits of our platform. Please order after changing the amount.</td>
</tr>
<tr>
<td>1045</td>
<td>Unable to switch leverage due to open orders.</td>
</tr>
<tr>
<td>1046</td>
<td>Abnormal service. Please try again later.</td>
</tr>
<tr>
<td>1047</td>
<td>Insufficient margin available.</td>
</tr>
<tr>
<td>1048</td>
<td>Insufficient close amount available.</td>
</tr>
<tr>
<td>1049</td>
<td>Open a position with market price is not available.contracts</td>
</tr>
<tr>
<td>1050</td>
<td>Customer's order number is repeated. Please try again later.</td>
</tr>
<tr>
<td>1051</td>
<td>No orders to cancel.</td>
</tr>
<tr>
<td>1052</td>
<td>The number exceeds the batch limit.</td>
</tr>
<tr>
<td>1053</td>
<td>Unable to get the latest price range.</td>
</tr>
<tr>
<td>1054</td>
<td>Unable to get the latest price.</td>
</tr>
<tr>
<td>1055</td>
<td>The price is not reasonable, and the account equity will be less than 0 after placing this order. Please modify the price and place the order.</td>
</tr>
<tr>
<td>1056</td>
<td>In settlement. Your order can’t be placed/withdrew currently.</td>
</tr>
<tr>
<td>1057</td>
<td>Your order can’t be placed due to trading halt.</td>
</tr>
<tr>
<td>1058</td>
<td>Your order can’t be placed due to trade suspension.</td>
</tr>
<tr>
<td>1059</td>
<td>In delivery. Your order can’t be placed/withdrew currently.</td>
</tr>
<tr>
<td>1060</td>
<td>Your order can’t be placed currently due to abnormal contracts status.</td>
</tr>
<tr>
<td>1061</td>
<td>This order doesn't exist.</td>
</tr>
<tr>
<td>1062</td>
<td>Cancelling. Please be patient.</td>
</tr>
<tr>
<td>1063</td>
<td>The order has been executed.</td>
</tr>
<tr>
<td>1064</td>
<td>The main key of order conflicts.</td>
</tr>
<tr>
<td>1065</td>
<td>The form number of client isn't an integer.</td>
</tr>
<tr>
<td>1066</td>
<td>{0} cannot be empty.</td>
</tr>
<tr>
<td>1067</td>
<td>Illegal parameter {0}.</td>
</tr>
<tr>
<td>1068</td>
<td>Export error.</td>
</tr>
<tr>
<td>1069</td>
<td>The price is not reasonable.</td>
</tr>
<tr>
<td>1070</td>
<td>Empty data, cannot be exported.</td>
</tr>
<tr>
<td>1071</td>
<td>Repeated cancellation. Your order has been canceled.</td>
</tr>
<tr>
<td>1072</td>
<td>Sell price must be lower than {0}{1}.</td>
</tr>
<tr>
<td>1073</td>
<td>Position abnormal. Please contact the customer service.</td>
</tr>
<tr>
<td>1074</td>
<td>Unable to order currently. Please contact the customer service.</td>
</tr>
<tr>
<td>1075</td>
<td>The price is not reasonable, and the margin rate will be less than 0 after placing this order. Please modify the price and place the order.</td>
</tr>
<tr>
<td>1076</td>
<td>No orders, please try again later.</td>
</tr>
<tr>
<td>1077</td>
<td>In settlement or delivery. Unable to get assets of current contract.</td>
</tr>
<tr>
<td>1078</td>
<td>In settlement or delivery. Unable to get assets of some contracts.</td>
</tr>
<tr>
<td>1079</td>
<td>In settlement or delivery. Unable to get positions of current contract.</td>
</tr>
<tr>
<td>1080</td>
<td>In settlement or delivery. Unable to get positions of some contracts.</td>
</tr>
<tr>
<td>1081</td>
<td>The number of your {0} contract trigger orders exceeds the limit {1}.</td>
</tr>
<tr>
<td>1082</td>
<td>Trigger type parameter error.</td>
</tr>
<tr>
<td>1083</td>
<td>Your position is in the process of forced liquidation. Unable to place order temporarily.</td>
</tr>
<tr>
<td>1084</td>
<td>Your contract API is disabled, please try again after {0} (GMT+8).</td>
</tr>
<tr>
<td>1085</td>
<td>Trigger order failed, please modify the price and place the order again or contact the customer service.</td>
</tr>
<tr>
<td>1086</td>
<td>{0} contract is restricted of opening positions on {1}.  Please contact customer service.</td>
</tr>
<tr>
<td>1087</td>
<td>{0} contract is restricted of closing positions on {1}.  Please contact customer service.</td>
</tr>
<tr>
<td>1088</td>
<td>{0} contract is restricted of withdraw order on {1}.  Please contact customer service.</td>
</tr>
<tr>
<td>1089</td>
<td>Transfer is temporarily restricted for {0} account, please contact customer service support.</td>
</tr>
<tr>
<td>1090</td>
<td>Margin rate is lower than 0. Order can’t be placed.</td>
</tr>
<tr>
<td>1091</td>
<td>Equity is less than 0. Order can’t be placed.</td>
</tr>
<tr>
<td>1092</td>
<td>The Flash Closing Order takes the {0}th price at the order book. After placing an order, the account equity will be less than 0. Please manually enter the price or place an order with the counterparty price.</td>
</tr>
<tr>
<td>1093</td>
<td>The Flash Closing Order takes the {0}th price at the order book. The margin rate will be less than 0 after placing an order. Please manually enter the price or place an order with the counterparty price.</td>
</tr>
<tr>
<td>1094</td>
<td>The leverage cannot be empty, please switch the leverage or contact customer service</td>
</tr>
<tr>
<td>1095</td>
<td>Non-trading state, unable to switch the leverage temporarily</td>
</tr>
<tr>
<td>1100</td>
<td>Unable to open a position currently. Please contact the customer service.</td>
</tr>
<tr>
<td>1101</td>
<td>Unable to close a position currently. Please contact the customer service.</td>
</tr>
<tr>
<td>1102</td>
<td>Unable to transfer in currently. Please contact customer service.</td>
</tr>
<tr>
<td>1103</td>
<td>Unable to transfer out currently. Please contact customer service.</td>
</tr>
<tr>
<td>1104</td>
<td>Trading is prohibited due to contracts trading constraints.</td>
</tr>
<tr>
<td>1105</td>
<td>Only Close is available due to contracts trading constraints.</td>
</tr>
<tr>
<td>1106</td>
<td>Delivery or settlement in progress, unable to transfer.</td>
</tr>
<tr>
<td>1108</td>
<td>Abnormal service. Please try again later.</td>
</tr>
<tr>
<td>1109</td>
<td>Sub-account doesn't own the permissions to open positions. Please contact customer service.</td>
</tr>
<tr>
<td>1110</td>
<td>Sub-account  doesn't own the permissions to close positions. Please contact customer service.</td>
</tr>
<tr>
<td>1111</td>
<td>Sub-account doesn't own the permissions to transfer in. Please contact customer service.</td>
</tr>
<tr>
<td>1112</td>
<td>Sub-account doesn't own the permissions to transfer out. Please contact customer service.</td>
</tr>
<tr>
<td>1113</td>
<td>The sub-account does not have transaction permissions. Please login main account to authorize.</td>
</tr>
<tr>
<td>1114</td>
<td>The sub-account does not have transfer permissions. Please login main account to authorize.</td>
</tr>
<tr>
<td>1115</td>
<td>You have no access permissions of this sub-account.</td>
</tr>
<tr>
<td>1200</td>
<td>Login error. Please try again.</td>
</tr>
<tr>
<td>1220</td>
<td>You don’t have access permission as you have not opened contracts trading.</td>
</tr>
<tr>
<td>1221</td>
<td>The total balances of Exchange Account can't meet the requirements for opening contracts.</td>
</tr>
<tr>
<td>1222</td>
<td>The days of opening account can't meet the requirements for opening contracts.</td>
</tr>
<tr>
<td>1223</td>
<td>The VIP level can't meet the requirements for opening contracts.</td>
</tr>
<tr>
<td>1224</td>
<td>Your country/region can't meet the requirements for opening contracts.</td>
</tr>
<tr>
<td>1225</td>
<td>Failed to open contracts.</td>
</tr>
<tr>
<td>1226</td>
<td>Repeated account.</td>
</tr>
<tr>
<td>1227</td>
<td>Huobi Contract does not support sub-accounts. Please log out sub-account and log in again with primary account.</td>
</tr>
<tr>
<td>1228</td>
<td>You have not activated contract trading currently, please activate first.</td>
</tr>
<tr>
<td>1229</td>
<td>Cannot agree twice.</td>
</tr>
<tr>
<td>1230</td>
<td>You haven't finished the risk verification.</td>
</tr>
<tr>
<td>1231</td>
<td>You haven't finished the ID Verification.</td>
</tr>
<tr>
<td>1232</td>
<td>The format/size of the image you uploaded does not meet the requirements. Please re-upload.</td>
</tr>
<tr>
<td>1233</td>
<td>High leverage is not enabled (Please sign in the APP or web with your main account to agree to the High-Leverage Agreement)</td>
</tr>
<tr>
<td>1234</td>
<td>For {0} contracts, the number of the position-opening orders which are not fully filled cannot exceed {1}.</td>
</tr>
<tr>
<td>1235</td>
<td>For {0} contracts, the number of the position-closing orders which are not fully filled cannot exceed {1}.</td>
</tr>
<tr>
<td>1250</td>
<td>Unable to get the HT_token.</td>
</tr>
<tr>
<td>1251</td>
<td>Unable to get BTC assets. Please try again later.</td>
</tr>
<tr>
<td>1252</td>
<td>Unable to get currency account assets. Please try again later.</td>
</tr>
<tr>
<td>1253</td>
<td>Error in signature verification.</td>
</tr>
<tr>
<td>1254</td>
<td>The sub-account has no permission to open futures, please go to the web side to log in the main account and open.</td>
</tr>
<tr>
<td>1300</td>
<td>Transfer failed.</td>
</tr>
<tr>
<td>1301</td>
<td>Insufficient amount available.</td>
</tr>
<tr>
<td>1302</td>
<td>Transfer failed.</td>
</tr>
<tr>
<td>1303</td>
<td>The single transfer-out amount must be no less than {0}{1}.</td>
</tr>
<tr>
<td>1304</td>
<td>The single transfer-out amount must be no more than {0}{1}.</td>
</tr>
<tr>
<td>1305</td>
<td>The single transfer-in amount must be no less than {0}{1}.</td>
</tr>
<tr>
<td>1306</td>
<td>The single transfer-in amount must be no more than {0}{1}.</td>
</tr>
<tr>
<td>1307</td>
<td>Your accumulative transfer-out amount is over the daily maximum, {0}{1}. You can't transfer out for the time being.</td>
</tr>
<tr>
<td>1308</td>
<td>Your accumulative transfer-in amount is over the daily maximum, {0}{1}. You can't transfer in for the time being.</td>
</tr>
<tr>
<td>1309</td>
<td>Your accumulative net transfer-out amount is over the daily maximum, {0}{1}. You can't transfer out for the time being.</td>
</tr>
<tr>
<td>1310</td>
<td>Your accumulative net transfer-in amount is over the daily maximum, {0}{1}. You can't transfer in for the time being.</td>
</tr>
<tr>
<td>1311</td>
<td>The platform's accumulative transfer-out amount is over the daily maximum. You can't transfer out for the time being.</td>
</tr>
<tr>
<td>1312</td>
<td>The platform's accumulative transfer-in amount is over the daily maximum. You can't transfer in for the time being.</td>
</tr>
<tr>
<td>1313</td>
<td>The platform's accumulative net transfer-out amount is over the daily maximum. You can't transfer out for the time being.</td>
</tr>
<tr>
<td>1314</td>
<td>The platform's accumulative net transfer-in amount is over the daily maximum. You can't transfer in for the time being.</td>
</tr>
<tr>
<td>1315</td>
<td>Wrong transfer type.</td>
</tr>
<tr>
<td>1316</td>
<td>Failed to freeze the transfer.</td>
</tr>
<tr>
<td>1317</td>
<td>Failed to unfreeze the transfer.</td>
</tr>
<tr>
<td>1318</td>
<td>Failed to confirm the transfer.</td>
</tr>
<tr>
<td>1319</td>
<td>Failed to acquire the available transfer amount.</td>
</tr>
<tr>
<td>1320</td>
<td>The contract status is abnormal. Transfer is unavailable temporarily.</td>
</tr>
<tr>
<td>1321</td>
<td>Transfer failed. Please try again later or contact customer service.</td>
</tr>
<tr>
<td>1322</td>
<td>Invalid amount. Must be more than 0.</td>
</tr>
<tr>
<td>1323</td>
<td>Abnormal service, transfer failed. Please try again later.</td>
</tr>
<tr>
<td>1325</td>
<td>Failed to set trading unit</td>
</tr>
<tr>
<td>1326</td>
<td>Failed to obtain trading units</td>
</tr>
<tr>
<td>1327</td>
<td>No transfer permission, transfer failed, please contact customer service</td>
</tr>
<tr>
<td>1328</td>
<td>No transfer permission, transfer failed, please contact customer service</td>
</tr>
<tr>
<td>1329</td>
<td>No transfer permission, transfer failed, please contact customer service</td>
</tr>
<tr>
<td>1330</td>
<td>No transfer permission, transfer failed, please contact customer service</td>
</tr>
<tr>
<td>1331</td>
<td>Exceeds limit of transfer accuracy (8 digits). Please modify it</td>
</tr>
<tr>
<td>1332</td>
<td>The contract doesn't exist.</td>
</tr>
<tr>
<td>1333</td>
<td>Failed to open the Maker&amp;Taker agreement</td>
</tr>
<tr>
<td>1334</td>
<td>Failed to check the Maker&amp;Taker agreement</td>
</tr>
<tr>
<td>1335</td>
<td>Failed to check the second confirmation setting of Maker&amp;Taker</td>
</tr>
<tr>
<td>1336</td>
<td>Failed to update the second confirmation setting of Maker&amp;Taker</td>
</tr>
<tr>
<td>1337</td>
<td>Failed to check the settings of Maker&amp;Taker</td>
</tr>
<tr>
<td>1338</td>
<td>Failed to update the settings of Maker&amp;Taker</td>
</tr>
<tr>
<td>1339</td>
<td>Nickname contains illegal words, please modify it</td>
</tr>
<tr>
<td>1340</td>
<td>Nickname has been used, please modify it</td>
</tr>
<tr>
<td>1341</td>
<td>The enrollment has ended</td>
</tr>
<tr>
<td>1342</td>
<td>You cannot set nickname for sub-account</td>
</tr>
<tr>
<td>1343</td>
<td>Invalid indicator, please reset</td>
</tr>
<tr>
<td>1344</td>
<td>Sorry, {0} contracts can add market reminders currently at most</td>
</tr>
<tr>
<td>1345</td>
<td>Sorry, currently {0} can set up to {1} reminders</td>
</tr>
<tr>
<td>1346</td>
<td>The indicator already exists, please do not set it repeatedly</td>
</tr>
<tr>
<td>1347</td>
<td>{0} parameter is incorrect, please modify.</td>
</tr>
<tr>
<td>1348</td>
<td>This contract does not support cross margin mode.</td>
</tr>
<tr>
<td>1349</td>
<td>The leverage of the order does not match the leverage of the current position, please switch the leverage first.</td>
</tr>
<tr>
<td>1401</td>
<td>order price shall be lower than the strike price.</td>
</tr>
<tr>
<td>1403</td>
<td>The number of take-profit and stop-loss orders for {0} contract shall not exceed {1}</td>
</tr>
<tr>
<td>1404</td>
<td>Take-profit and stop-loss orders can only be bound with orders for opening a position</td>
</tr>
<tr>
<td>1405</td>
<td>The take-profit price shall not be {0}{1}{2}</td>
</tr>
<tr>
<td>1406</td>
<td>Your chances of lucky draw have been used up</td>
</tr>
<tr>
<td>1407</td>
<td>The stop-loss price shall not be {0}{1}{2}</td>
</tr>
<tr>
<td>1408</td>
<td>Unable to cancel because the take-profit and stop-loss order does not take effect.</td>
</tr>
<tr>
<td>1409</td>
<td>You have no access to set a take-profit and stop-loss order, please contact our customer service.</td>
</tr>
<tr>
<td>1410</td>
<td>The number of sub-accounts for batch operation cannot exceed {0}</td>
</tr>
<tr>
<td>1411</td>
<td>Settlement in progress, unable to query order information.</td>
</tr>
<tr>
<td>1412</td>
<td>{0} does not meet with the price precision limit {1}.</td>
</tr>
<tr>
<td>1413</td>
<td>You have no access to set a Trailing Stop order, please contact our customer service.</td>
</tr>
<tr>
<td>1414</td>
<td>You have not activated the grid trading. Please log in to the Web or APP with your main account, and agree with the protocol to activate the grid trading.</td>
</tr>
<tr>
<td>1415</td>
<td>Terminate price (Take-profit/Stop-loss price) cannot be within the range of grid price, please modify!</td>
</tr>
<tr>
<td>1416</td>
<td>Exceeds the maximum running time, which is{0} days and {1} hours, please modify!</td>
</tr>
<tr>
<td>1417</td>
<td>Exceeds the range of grid quantity, which is ({0} ~ {1}), please modify!</td>
</tr>
<tr>
<td>1418</td>
<td>At most {0} grids trading orders can be running at the same time, please cancel other grid trading orders first.</td>
</tr>
<tr>
<td>1419</td>
<td>Exceeds the range of initial margin ({0} ~ {1}} {2}).</td>
</tr>
<tr>
<td>1420</td>
<td>You have no access to grid trading on Huobi Futures, please contact our customer service.</td>
</tr>
<tr>
<td>1421</td>
<td>There are open orders or positions of the current contract, please cancel these orders or close these positions first.</td>
</tr>
<tr>
<td>1422</td>
<td>The PnL per grid is expected to be less than 0, please modify!</td>
</tr>
<tr>
<td>1423</td>
<td>The spread between the lowest and the highest grid price is unreasonable, please modify!</td>
</tr>
<tr>
<td>1424</td>
<td>This grid trading has been terminated for other reasons. Therefore, it cannot be modified or manually terminated now.</td>
</tr>
<tr>
<td>1425</td>
<td>The callback rate should be {0}{1}, please modify!</td>
</tr>
<tr>
<td>1426</td>
<td>The activation price should be {0} the latest price.</td>
</tr>
<tr>
<td>1427</td>
<td>The number of your {0} contract trailing stop order orders exceeds the limit {1}.</td>
</tr>
<tr>
<td>1428</td>
<td>The coupon for the same type of contract can only be collected once by each user.</td>
</tr>
<tr>
<td>1429</td>
<td>Already received; please do not collect again!</td>
</tr>
<tr>
<td>1430</td>
<td>Invalid coupon; please refresh!</td>
</tr>
<tr>
<td>1431</td>
<td>The system is in maintenance and is expected to resume at {0} (GMT+8).</td>
</tr>
<tr>
<td>12001</td>
<td>Invalid submission time.</td>
</tr>
<tr>
<td>12002</td>
<td>Incorrect signature version.</td>
</tr>
<tr>
<td>12003</td>
<td>Incorrect signature method.</td>
</tr>
<tr>
<td>12004</td>
<td>Private key is expired.</td>
</tr>
<tr>
<td>12005</td>
<td>Incorrect IP address.</td>
</tr>
<tr>
<td>12006</td>
<td>The submission time can't be empty.</td>
</tr>
<tr>
<td>12007</td>
<td>Incorrect public key.</td>
</tr>
<tr>
<td>12008</td>
<td>Verification failed.</td>
</tr>
<tr>
<td>12009</td>
<td>The user is locked or doesn't exist.</td>
</tr>
</tbody></table>
<h2 id="api-best-practice">API Best Practice</h2><h3 id="1-query-contract-history-orders-interface-swap-api-v1-swap_hisorders">1. Query contract history orders interface: /swap-api/v1/swap_hisorders</h3>
<ul>
<li><p>To ensure timelines and to reduce latency, users are highly recommended to get contract history orders information faster from server memory using interface “query contract order information” (URL: /swap-api/v1/swap_order_info).</p></li>
<li><p>For users who use interface “query contract history orders” (URL: //swap-api/v1/swap_hisorders), please enter as many query conditions as possible (including contract_code, trade_type（recommended to send “0” to query all）, type, status, create_date). Besides, try not to enter a big integer in parameter “create_date”. You are kindly suggested to query one-day data at a time.</p></li>
</ul>
<h3 id="2-query-contract-match-results-interface-swap-api-v1-swap_matchresults">2. Query contract match results interface: /swap-api/v1/swap_matchresults</h3>
<ul>
<li>To improve query performance and response speed, please enter as many querying conditions as possible (including contract_code, trade_type（recommended to send “0” to query all）, create_date). Besides, try not to enter a big integer in parameter “create_date”. You are kindly suggested to query one-day data at a time.</li>
</ul>
<h3 id="3-query-contract-financial-record-interface-swap-api-v1-swap_financial_record">3. Query contract financial record interface: /swap-api/v1/swap_financial_record</h3>
<ul>
<li>To improve query performance and response speed, please enter as many querying conditions as possible (including symbol, type(recommended to leave it blank to query all), create_date). Besides, try not to enter a big integer in parameter “create_date”. You are kindly suggested to query one-day data at a time.</li>
</ul>
<h3 id="4-query-contract-order-detail-interface-swap-api-v1-swap_order_detail">4. Query contract order detail interface: /swap-api/v1/swap_order_detail</h3>
<ul>
<li><p>When querying orders without parameter(such as the parameter: created_at), the query result data may be delayed. It is recommended to pass the two parameters of the interface: created_at (order timestamp) and order_type (order type, default 1), the database will be directly queried, and the query results data will be more timely.</p></li>
<li><p>Querying condition “created_at” uses 13-bit long type time stamp (including milliseconds). Querying performance will be improved when accurate time stamps are entered.</p></li>
<li><p>For example: the converted time stamp of "2019/10/18 10:26:22" is 1571365582123. The returned ts from interface “contract_order” can be used as time stamp to query corresponding order. 0 is not allowed in parameter “created_at”.</p></li>
</ul>
<h3 id="5-websocket-subscription-to-market-depth-data">5. WebSocket subscription to Market Depth data:</h3>
<ul>
<li><p>For acquiring market depth data within 150 steps, you are kindly suggested to use step0, step1, step2, step3, step4, step5, step14, step15；</p></li>
<li><p>For acquiring market depth data within 20 steps, you are kindly suggested to use step6, step7, step8, step9, step10, step11, step12, step13；</p></li>
<li><p>Since the large volume of pushing 150 steps data every 100ms, WebSocket disconnection may occur frequently if client’s network bandwidth is insufficient or the processing is not in time; therefore, we highly recommend users using step6, step7, step8, step9, step10, step11, step12, step13 to acquire 20 steps data. For instance, subscribing 20 steps data.</p></li>
</ul>

<p><code>{</code></p>

<p><code>"sub": "market.BTC-USD.depth.step6",</code></p>

<p><code>"id": "id5"</code></p>

<p><code>}</code></p>

<ul>
<li>We also suggest that you subscribe incremental market depth data.orderbook event will be checked every 30ms. If there is no orderbook event, you will not receive any orderbook data.you HAVE TO maintain local orderbook data,such as updating your local orderbook bids and asks data.You can subscribe 20 or 150 unmerged data.</li>
</ul>

<p><code>{</code></p>

<p><code>"sub": "market.BTC-USD.depth.size_20.high_freq",</code></p>

<p><code>"data_type":"incremental",</code></p>

<p><code>"id": "id1"</code></p>

<p><code>}</code></p>
<h3 id="6-place-order-interface-url-swap-api-v1-swap_order-and-place-a-batch-of-orders-interface-url-swap-api-v1-swap_batchorder">6. Place order interface (URL: /swap-api/v1/swap_order) and place a batch of orders interface (URL:/swap-api/v1/swap_batchorder):</h3>
<ul>
<li><p>We recommend to fill in the parameter “client_order_id”(should be unique from user-side),which can help users to acquire order status and other order information according to the parameter “client_order_id" from</p></li>
<li><p>query order information interface (URL: /swap-api/v1/swap_order_info ) when there is no returned information due to network or other problems.</p></li>
</ul>
<h2 id="code-demo">Code Demo</h2>
<p>PS: Coin Margined Swap api is similar to future api.</p>
<h3 id="rest">REST</h3>
<ul>
<li><p><a href="https://github.com/hbdmapi/java_demo">Java</a></p></li>
<li><p><a href="https://github.com/hbdmapi/hbdm_Python">Python</a></p></li>
<li><p><a href="https://github.com/hbdmapi/hbdm_swap_Rust">Rust</a></p></li>
<li><p><a href="https://github.com/hbdmapi/huobi_swap_Cpp">C++</a></p></li>
<li><p><a href="https://github.com/hbdmapi/huobi_futures_Postman">Postman</a></p></li>
</ul>
<h3 id="contract-sdk">Contract SDK</h3>
<ul>
<li><a href="https://github.com/hbdmapi/huobi_coin_swap_Java">Java SDK</a></li>
</ul>
<h1 id="swap-api-faq">Swap API FAQ</h1><h2 id="access-and-authentication">Access and Authentication</h2><h3 id="q1-is-the-api-key-for-future-and-spot-the-same">Q1: Is the API Key  for future and spot the same ?</h3>
<p>Yes. The future API key and spot API key are same. You can create API using the following link.<a href="https://www.hbg.com/zh-cn/apikey/"> click here</a></p>
<h3 id="q2-why-are-apis-disconnected-or-timeout">Q2: Why are APIs  disconnected or timeout?</h3>
<ol>
<li><p>The network connection is unstable if the server locates in China mainland,it is suggested to invoke APIS from a server located in  1c area of AWS Tokyo.</p></li>
<li><p>You can use api.btcgateway.pro or api.hbdm.vn to debug for China mainland  network.</p></li>
</ol>
<h3 id="q3-why-is-the-websocket-often-disconnected">Q3: Why is the websocket often disconnected?</h3>
<p>It seems that most of the abnormal websocket  issues (such as disconnect, websocket close )(websocket: close 1006 (abnormal closure))are caused by different network environment. The following measures can effectively reduce websocket issues.</p>

<p>It would be better if the server is located in 1c area of AWS Tokyo with url api.hbdm.vn and implement websocket re-connection mechanism. Both market heartbeat and order heartbeat should response with Pong with different format, following  Websocket market heartbeat and account heartbeat requirement.<a href="https://docs.huobigroup.com/docs/coin_margined_swap/v1/cn/#472585d15d">here</a></p>
<h3 id="q4-what-is-the-difference-between-api-hbdm-com-and-api-hbdm-vn">Q4:  what is the difference between api.hbdm.com and api.hbdm.vn?</h3>
<p>The api.hbdm.vn uses AWS's CDN service. it should be more stable and faster for AWS users. The api.hbdm.com uses Cloudflare's CDN service</p>
<h3 id="q5-what-is-the-colocation-service-which-attention-points-should-we-know">Q5: What is the colocation service ? which attention points should we know ?</h3>
<p>Actually ,colo corresponds to a vpc node, which directly connects to  private network of huobi's future, so it will reduce the latency between the client and the Huobi future server (bypassing the CDN)</p>

<p>huobi future and huobi swap have the same colo, so the domain name connecting the swap api and the future api are the same.</p>

<p>Note : Colo needs to use api.hbdm.com for signature(authentication) to avoid getting 403 error: Verification failure. </p>
<h3 id="q6-why-does-signature-verification-return-failure-403-verification-failure">Q6: Why does signature verification return failure (403: Verification failure) ?</h3>
<p>The signature process of coin margined swap is similar to huobi future . In addition to the following precautions,please refer to the future demo to verify whether the signature is successful. Please check your own signature code after demo verification is successful. The coin margined  swap code demo is <a href="https://docs.huobigroup.com/docs/coin_margined_swap/v1/en/#code-demo">here</a>. The future code demo is <a href="https://docs.huobigroup.com/docs/dm/v1/en/#code-demo">here</a>.The option code demo is <a href="https://docs.huobigroup.com/docs/option/v1/en/#code-demo">here</a>. The USDT Margined Swap code demo is <a href="https://docs.huobigroup.com/docs/usdt_swap/v1/en/#code-demo">here</a>.</p>

<ol>
<li>Check if the API key is valid and copied correctly.</li>
<li>Check if the IP is in whitelist</li>
<li>Check if th timestamp is UTC time</li>
<li>Check if parameters are sorted alphabetically</li>
<li>Check if the encoding is UTF-8 </li>
<li>Check if the signature has base64 encoding</li>
<li>Any method with parameters for GET requests should be signed.</li>
<li>Any method with parameters for POST requests don't need to be signed.</li>
<li>Check if whether the signature is URI encoded and Hexadecimal characters must be capitalized, such as ":" should be encoded as "%3A", and the space shoule be encoded as "%20"</li>
<li>The authorization of websocket is similar to the authorization of restful interface.Pls note that the json body of the websocket authorization shouldn't be URL encoded</li>
<li>The host in signature text should be the same as the host in your API request.The proxy may change the request host, you can try without proxy;Some http/websocket library may include port in the host, you can try to append port in signature host, like "api.hbdm.com:443"</li>
<li>The hidden text in API Key and Secret Key may have impact on the signature.</li>
</ol>
<h3 id="q7-is-the-ratelimit-of-public-market-based-on-ip-is-the-ratelimit-of-interface-with-private-key-based-on-uid">Q7: Is the ratelimit of public market based on  IP ? Is the ratelimit of interface with  private key based on UID?</h3>
<p>Yes. The ratelimit of interface with private key is based on the UID, not the API key. The master and sub accounts are separately ratelimited and don't affect each other.</p>
<h3 id="q8-is-there-any-recommendation-for-third-party-framework-which-integrates-huobi-swap">Q8: Is there any recommendation for third-party framework which integrates Huobi swap?</h3>
<p>There is an open source asynchronous quantization framework which integrates Huobi future and Huobi swap: <a href="https://github.com/hbdmapi/hbdm_Python">here</a>. If you have any quetsions, please open a ticket in github issues.</p>
<h2 id="market-and-websocket">Market and Websocket</h2><h3 id="q1-how-often-are-the-snapshot-orderbook-subscription-and-incremental-orderbook-subscription-pushed">Q1: How often are the snapshot orderbook subscription and incremental orderbook subscription pushed?</h3>
<p>The snapshot orderbook subscription(market.$contract_code.depth.$type) is checked once every 100MS.If there is an update,it will be pushed. It will be pushed at least 1 second.The incremental orderbook subscription is checked once every 30MS.If there is an update,it will be pushed.If there is no update, it will not be pushed.</p>
<h3 id="q2-how-often-is-the-market-trade-subscription-pushed">Q2: How often is the market trade subscription pushed?</h3>
<p>The market trade subscription will be pushed when there is a transaction. </p>
<h3 id="q3-are-there-historical-kline-data-or-historical-market-trade-data">Q3: Are there historical Kline data or historical market trade data?</h3>
<p>Historical Kline data can be obtained through the API interface:swap-ex/market/history/kline.Only the from and to parameters need to be filled in, and the size parameter is not needed.At most, only two consecutive years of data can be obtained.</p>

<p>The historical market trade data is currently not available, you can store it locally by subscribing to market trade: market.$Contract_code.trade.detail.</p>
<h3 id="q4-how-to-get-macd-and-other-technical-indicators-on-kline">Q4: How to get MACD and other technical indicators on Kline?</h3>
<p>The API does not have interfaces to get technical indicators such as MACD. You can refer to TradingView and other websites to calculate them.</p>
<h3 id="q5-what-is-the-definition-of-timestamp-in-the-document">Q5: What is the definition of timestamp in the document?</h3>
<p>The timestamp in the document refers to the total number of seconds or total milliseconds from Greenwich Mean Time, January 1, 1970, 00:00:00 (Beijing Time, January 1, 1970, 08:00:00) to the present.</p>
<h3 id="q6-what-is-the-definition-of-the-150-level-and-20-level-of-mbp">Q6: What is the definition of the 150 level and 20 level of MBP?</h3>
<p>The Subscription of MBP data: market.$contract_code.depth.$type.150 price level means the current bids and asks splited into 150 level  by price.20 price level means the current bids and asks splited into 20 level by price.</p>
<h3 id="q7-what-is-the-meaning-of-merged-depth-when-subscribing-mbp-data">Q7: What is the meaning of merged depth when subscribing MBP data?</h3>
<p>The subscrpition of MBP data:market.$contract_code.depth.$type：</p>

<p>step1 and step7 are merged by 5 decimal places.bids down,asks up.
step2 and step8 are merged by 4 decimal places.bids down,asks up.
step3 and step9 are merged by 3 decimal places.bids down,asks up.
step4 and step10 are merged by 2 decimal places.bids down,asks up.
step5 and step11 are merged by 1 decimal places.bids down,asks up.
step12 and step14 are combined by single digit.bids down,asks up.
step13 and step15 are combined by tens.bids down,asks up.</p>

<p>Example:</p>

<p>step4(0.01): </p>

<p>bids price: 100.123, 100.245.
The merged bids price are 100.12, 100.24.</p>

<p>asks price: 100.123, 100.245
The merged asks price are 100.13, 100.25.</p>

<p>("Down" and "Up" are rounded up or down, if the price is down, the asks price is not rounded down, and the bids price is rounded up.)</p>

<p>150 price level: step0 to step5, step14, step15；</p>

<p>20 price level: step6 to step13;</p>

<p>More examples：</p>

<p>step1(0.00001):</p>

<p>price: 1.123456
The merged bid price is 1.12345.
The merged ask price is 1.12346.</p>

<p>step7(0.00001):</p>

<p>price: 1.123456
The merged bid price is 1.12345.
The merged ask price is 1.12346.</p>

<p>step6(0.000001)</p>

<p>price: 1.123456
The merged bid price is 1.123456.
The merged ask price is 1.123456.</p>

<p>step11(0.1):</p>

<p>price: 1.123456
The merged bid price is 1.1.
The merged ask price is 1.1.</p>
<h3 id="q8-does-websocket-39-s-position-channel-push-full-data-or-incrementall-data-each-time">Q8:Does websocket's position channel push full data or incrementall data each time?</h3>
<p>Subscription of position event: "positions.BTC-USD".The latest position is pushed,including the volumes, available volumes, frozen volumes.If there is no update,it will not be pushed. </p>
<h3 id="q9-does-websocket-39-s-position-channel-push-data-when-the-unrealized-profit-is-updated">Q9: Does websocket's position channel push data when the unrealized profit is updated?</h3>
<p>Subscription of position event: "positions.BTC-USD".It will not be pushed  if only unrealized profit is updated.
It will be pushed only when position event is updated.</p>
<h3 id="q10-what-is-the-difference-between-market-detail-and-trade-detail-in-ws">Q10: What is the difference between market detail and trade detail in WS?</h3>
<p>Market Detail(market.$contract_code.detail) is the merged market data. It will be checked every 0.5s,pushed once trade event updates,including the OHLCV data,etc.Trade Detail(market.$contract_code.trade.detail) is pushed once trade event updates,including trade price, trade volume, trade direction,etc.</p>
<h3 id="q11-what-is-the-meaning-of-the-two-ts-pushed-by-subscription-of-incremental-mbp">Q11: What is the meaning of the two ts pushed by subscription of incremental MBP ?</h3>
<p>Subscription of incremental MBP：market.$contract_code.depth.size_${size}.high_freq，The outer ts is the timestamp when the market server sends the data.The inner ts is the timestamp when the orderbook is checked.</p>
<h3 id="q12-what-is-the-difference-between-websocket-subscription-of-mbp-and-incremental-mbp-how-often-is-the-incremental-mbp-pushed">Q12: What is the difference between websocket subscription of MBP and incremental MBP? How often is the incremental MBP pushed?</h3>
<p>market.$contract_code.depth.$type is snapshot MBP data，market.$contract_code.depth.size_${size}.high_freq is incremental MBP data.Snapshot MBP data is checked every 100ms,pushed at least every 1s.Incremental MBP data is checked every 30ms.It will not be pushed,if MBP has no update.</p>
<h3 id="q13-how-to-maintain-local-mbp-data-subscribing-incremental-mbp-market-contract_code-depth-size_-size-high_freq">Q13: How to maintain local MBP data subscribing incremental MBP:market.$contract_code.depth.size_${size}.high_freq?</h3>
<p>Snapshot MBP data will be pushed for the first time, and the incremental MBP data will be pushed afterwards.</p>

<p>(1) Compare the incremental price with the previous full MBP data, and replace the order amount with the same price;</p>

<p>(2) If the price is not in the local MBP data,add the price to the local MBP data;</p>

<p>(3) If a price level is gone, data such as [8100, 0] will be pushed.You have to remove the same price of local MBP data;</p>

<p>(4) For the same websocket connection, the incremental data version is incremented; if the version is not incremented, you need to re-subscribe and re-maintain the local full MBP data;</p>
<h3 id="q14-what-39-s-the-difference-between-quot-funding_rate-quot-and-quot-realized_rate-quot-in-the-response-of-swap-api-v1-swap_historical_funding_rate-interface">Q14: What's the difference between "funding_rate" and "realized_rate" in the response of swap-api/v1/swap_historical_funding_rate interface?</h3>
<p>Generally, "funding_rate" is equal to "realized_rate".Only when the payment of funding fee will cause the liquidation of the user's position, the funding fee is under or not charged(And the fee is the actual funding fee:"realized_rate").The current funding rate:"funding_rate" remains unchanged.</p>
<h3 id="q15-when-subscribing-the-same-topic-of-several-contract-codes-will-several-ws-be-needed">Q15: When subscribing the same topic of several contract codes, will several ws be needed?</h3>
<p>Since Futures, Coin Margined swaps, USDT Margined swaps and Options are different contracts with different interface addresses, different ws will be needed.</p>

<p>In Futures, Coin Margined swaps, USDT Margined swaps and Options thereof, as long as the interface address is the same, one ws is enough.</p>
<h3 id="q16-is-it-available-to-place-cancel-an-order-via-ws">Q16: Is it available to place/cancel an order via WS??</h3>
<p>Currently, it is not supported.</p>
<h3 id="q17-how-to-subscribe-order-status">Q17: How to subscribe order status?</h3>
<p>a.  Successfully trade: “Subscribe Match Order Data (matchOrders.$contract_code)” or “Subscribe Order Data (orders.$contract_code)”</p>

<p>b.  Successfully cancel: Subscribe Account Equity Updates Data (accounts.$contract_code)</p>
<h3 id="q18-what-is-the-difference-between-the-subscribe-match-order-data-matchorders-contract_code-and-subscribe-order-data-orders-contract_code">Q18: What is the difference between the “Subscribe Match Order Data (matchOrders.$contract_code)” and “Subscribe Order Data (orders.$contract_code)”?</h3>
<p>The pushed data of these two interfaces are different. Compared to “Subscribe Match Order Data (matchOrders.$contract_code)”, there are more fields for “Subscribe Order Data (orders.$contract_code)”</p>

<p>In general, the match order data (Subscribe Match Order Data “matchOrders.$contract_code”) may be pushed faster than the settled order data (Subscribe Order Data “orders.$contract_code”). </p>

<p>The orders of forced liquidation and netting will not be pushed in “Subscribe Match Order Data (matchOrders.$contract_code)”</p>
<h3 id="q19-how-often-is-the-subscribe-kline-data-market-contract_code-kline-period-pushed">Q19: How often is the “Subscribe Kline Data (market.$contract_code.kline.$period)” pushed?</h3>
<p>If any transaction is completed, it will push every 500ms. If not, it will push according to the subscribe period</p>
<h3 id="q20-how-to-judge-whether-the-push-is-delayed">Q20: How to judge whether the push is delayed?</h3>
<p>Please first synchronize the time of the server through https://api.hbdm.com/api/v1/timestamp), and the “ts” in the returned data is timestamp (ms) and the corresponding time zone is UTC+8.</p>

<p>The outer layer of each pushed data has a “ts”, which represents the time stamp (ms) when the server pushes the data to the client and the corresponding time zone is UTC+8.</p>

<p>When the data pushed arrive, the procedure will record the local time “ts”. When the local time “ts” is much later than the pushing data “ts”, you can use the following methods to improve the delay:</p>

<p>a. Reduce the data pushed by reducing the number of WS subscriptions.</p>

<p>b. Check the stability and speed of the network between procedure and the servers (please replace api.btcgateway.pro with the domain name used by the program)</p>

<p>curl -o /dev/null -s -w time_namelookup"(s)":%{time_namelookup}"\n"time_connect"(s)":%{time_connect}"\n"time_starttransfer"(s)":%{time_starttransfer}"\n"time_total"(s)":%{time_total}"\n"speed_download"(B/s)":%{speed_download}"\n" api.btcgateway.pro</p>

<p>and you will receive data as below:</p>

<p>time_namelookup(s):0.001378</p>

<p>time_connect(s):0.128641</p>

<p>time_starttransfer(s):0.276588</p>

<p>time_total(s):0.276804</p>

<p>speed_download(B/s):2010.000</p>

<p>If you run the above command multiple times in a row, and the results obtained each time are very different, you can: a. Select an appropriate Huobi domain name, b. Optimize or reselect the network where the program is located.</p>
<h2 id="order-and-trade">Order and Trade</h2><h3 id="q1-what-is-the-perpetual-funding-rate-settlement-cycle-which-interface-can-be-used-to-check-the-status-when-the-fund-rate-is-settled">Q1: What is the perpetual funding rate settlement cycle? Which interface can be used to check the status when the fund rate is settled?</h3>
<p>We warmly remind you that Huobi Perpetual Swaps is settled every 8 hours, and the settlement will be at the end of each period. For example, 00:00 - 08:00 is a period, and its settlement time would be at 08:00; 08:00 - 16:00 is a period, and its settlement time would be at 16:00; 16:00 - 00:00 (+1 day) is a period, and its settlement time would be at 00:00. All times mentioned above are Singapore Standard time (GMT+8).</p>

<p>（1）Orders can't be placed or cancelled during settlement period, error code "1056" will be returned if users place or cancel orders. You are recommended to request contract information every few seconds during settlement period: swap-api/v1/swap_contract_info. It's in settlement time if there is any number of 5, 6, 7, 8 included in the returned status code of contract_status, while it indicates that settlement completed and users could place and cancel orders as usual if the returned status code is 1.</p>

<p>（2）When querying fund or position information during the settlement period, error codes will be returned. Error code and their meaning are as following:</p>

<p>Error code "1077" indicates that "the fund query of current perpetual swap trading pair failed during the settlement";
Error code "1078" indicates that "the fund query of part of perpetual swap trading pairs failed during the settlement";
Error code "1079" indicates that "the position query of current perpetual swap trading pair failed during the settlement";
Error code "1080" indicates that "the position query of part of perpetual swap trading pairs failed during the settlement";
You are recommended to read the status code from the returned message. If the above four types of status code appear, the returned data is not accurate and couldn't be used as reference.</p>
<h3 id="q2-what-39-s-the-reason-for-1004-error-code">Q2: What's the reason for 1004 error code?</h3>
<p>We notice that the system is sometimes overloaded when the market suddenly turns to be highly volatile. If the system is busy recently or the following prompts appear:</p>

<p>{“status”: “error”, “err_code”: 1004, “err_msg”: “System busy. Please try again later.”, “ts”:}</p>

<p>please be patient, and do not place or cancel order repeatedly during the process to avoid repeated orders and additional pressure on system performance. In the meanwhile, it is recommended to place and cancel orders through Web and APP.</p>
<h3 id="q3-the-same-order-id-and-match-id-can-have-multiple-trades-for-example-if-a-user-take-a-large-amount-of-maker-orders-there-will-be-multiple-corresponding-trades-how-to-identify-these-different-trades">Q3: The same order ID and match ID can have multiple trades. for example: if a user take a large amount of maker orders, there will be multiple corresponding trades . How to identify these different trades ?</h3>
<p>The field ID returned by the information interface swap-api/v1/swap_order_detail is a globally unique transaction identifier. if a maker order is matched multiple times, a trade will be pushed once there is a transaction matched.</p>
<h3 id="q4-what-is-the-delay-for-the-round-trip-of-huobi-swap">Q4: What is the delay for the round trip of huobi swap?</h3>
<p>At present,it normally takes about 30-50ms from placing the order to getting the status of the order.</p>
<h3 id="q5-why-does-the-api-return-connection-reset-or-max-retris-or-timeout-error">Q5: Why does the API return connection reset or Max retris or Timeout error?</h3>
<p>Most of the network connectivity problems ,(such as Connection reset or network timeout )  are caused by network instability , you can use the server in AWS Tokyo C area with api.hbdm.vn , which can effectively reduce network timeout errors.</p>
<h3 id="q6-how-to-check-the-order-status-without-order_id-not-returned">Q6: How to check the order status without order_id not returned?</h3>
<p>If the order_id couldn't be returned due to network problems, you can query the status of the order by adding the custom order number(client_order_id ).</p>
<h3 id="q7-what-to-do-if-it-39-s-diconnected-after-the-websocket-subscription-of-account-order-and-positions-for-a-while">Q7: What to do if it's diconnected after the websocket subscription of account, order and positions for a while?</h3>
<p>When subscribing private accounts, orders and positions, the heartbeat should also be maintained regularlyl ,which is different from the market heartbeat format . Please refer to the "websocket Heartbeat and Authentication Interface" . if the it is disconnected ,please try to reconnect.</p>
<h3 id="q8-what-is-the-difference-between-order-status-1-and-2-what-is-the-status-3">Q8. What is the difference between order status 1 and 2 ? what is the status 3 ?</h3>
<p>Status 1 is the preparation for submission. status 2 is the sequential submission  of internal process, which can be considered that it has been accepted by the system.  Status 3 indicated that the order has been  already submitted to market.</p>
<h3 id="q9-is-there-an-interface-to-get-the-total-assets-in-btc-of-my-account">Q9. Is there an interface to get the total assets in BTC of my account ?</h3>
<p>No.</p>
<h3 id="q10-why-is-the-order-filled-after-the-order-is-withdrawed-successfully-by-placing-api-cancellation">Q10.  Why is the order filled after the order is withdrawed successfully by placing API cancellation ?</h3>
<p>The success return of order cancellation or placement  only represents that the command is excuted successfully and doesn't mean that the order has been cancelled . You can check the order status through the interface swap-api/v1/swap_order_info.</p>
<h3 id="q11-does-the-order-status-of-10-mean-the-order-is-failed">Q11: Does the order status of 10 mean the order is failed?</h3>
<p>Query the order status by swap-api/v1/swap_order_info.If the status is 10,the order is failed。</p>
<h3 id="q12-how-long-does-it-generally-take-for-an-api-from-withdrawing-to-cancelling-successfully">Q12: How long does it generally take for an API from withdrawing to cancelling successfully ?</h3>
<p>The order cancellation command generally takes several tens of ms. The actual status of order cancellation can be obtained by invoking an interface: swap-api/v1/swap_order_info</p>
<h3 id="q13-how-to-get-historical-liquidation-orders">Q13: How to get historical liquidation orders?</h3>
<p>To obtain historical liquidation orders, you can access the one of four api interfaces: Get History Orders (/swap-api/v1/swap_hisorders), Get History Match Results (/swap-api/v1/swap_matchresults), Query history orders via multiple fields (/swap-api/v1/swap_hisorders_exact), Query history transactions via multiple fields (/swap-api/v1/swap_matchresults_exact), with the return field order_source (order source) to judge. When order_source returns "risk", it means that this order is a liquidated order.</p>
<h3 id="q14-how-to-query-the-system-status-of-the-exchange">Q14: How to query the system status of the exchange?</h3>
<p>There are two common statuses of the exchange systems: settlement/delivery in progress; suspended for maintenance; when the system is in these two kinds of statuses, the system will return the response error code and error information when calling the related API interfaces.</p>

<p>a.  How to judge whether the settlement/delivery has been done?
Users can judge from the value “contract_status” returned by the “Get Information of an Order” interface ( /swap-api/v1/swap_contract_info); If the value turns out 1, it means that the settlement/delivery has been done and the trading has been resumed now.</p>

<p>b. How to judge whether the system is suspended for maintenance or not?
Users can judge from the value “heartbeat” pushed by the “Queried if system interface is available” interface (https://api.hbdm.com/heartbeat/) or the “Subscribe system status updates” interface ("topic: public.$service.heartbeat"); If the value turns out 1, it means that the system is available now and can be connected normally.</p>
<h3 id="q15-does-huob-futures-support-holding-bi-directional-position">Q15: Does Huob Futures support holding bi-directional position?</h3>
<p>Yes, Huobi Futures supports long and short positions being held at the same time.</p>
<h3 id="q16-how-to-ensure-the-order-to-be-rapidly-filled">Q16: How to ensure the order to be rapidly filled?</h3>
<p>At present, Huobi Futures does not support market price when placing an order. To increase the probability of a transaction, users can choose to place an order based on BBO price (opponent), optimal 5 (optimal_5), optimal 10 (optimal_10), optimal 20 (optimal_20), among which the success probability of optimal 20 is the largest, while the slippage always is the largest as well.</p>

<p>It is important to note that the above methods will not guarantee the order to be filled in 100%. The system will obtain the optimal N price at that moment and place the order.</p>
<h3 id="q17-how-can-api-procedure-be-connected-to-the-exchange-more-rapidly">Q17: How can API procedure be connected to the exchange more rapidly?</h3>
<p>It’s recommended to use a AWS Tokyo c-zone server and the domain name “api.hbdm.vn” to connect to the system.</p>
<h3 id="q18-it-occurs-an-abnormal-service-error-when-transferring-assets-between-spots-and-derivatives">Q18: It occurs an “abnormal service” error when transferring assets between spots and derivatives.</h3>
<p>a. Check whether the request address is the address of Huobi Global : api.huobi.pro?</p>

<p>b. Check whether the precision of the coin does not exceed 8 decimal places? </p>
<h3 id="q19-how-to-confirm-whether-the-position-is-opened-or-closed-successfully">Q19: How to confirm whether the position is opened or closed successfully?</h3>
<p>Placing an order successfully through “Place an Order” interface (/swap-api/v1/swap_order) or “Place a batch of orders” interface (/swap-api/v1/swap_batchorder) just means the server has received your order placing instructions rather than you have opened/closed a position successfully.</p>

<p>You can check the order status by filling the returned “order_id” in the “Get Information of an Order” interface (/swap-api/v1/swap_order_info) or the “Order Details Acquisition” interface (/swap-api/v1/swap_order_detail); If the order has been filled, the “status” value in the return parameter will turn out 6 (wholly filled)</p>

<p>It is important to note:</p>

<p>a.  For “Get Information of an order” interface (/swap-api/v1/swap_order_info), after the settlement or delivery, the system will delete all the orders in ended status (5: partially filled orders have been cancelled; 6: wholly filled; 7: cancelled);</p>

<p>b.  b. There is a delay in “Order Details Acquisition” interface (/swap-api/v1/swap_order_detail), so it is better to fill in “created_at” (order timestamp) and “order_type” (order type, fill in 1 by default). In this way, it will directly query the database, so the query results will be more timely.</p>
<h3 id="q20-why-are-orders-canceled-by-the-system-automatically">Q20: Why are orders canceled by the system automatically?</h3>
<p>The order_price_type which can be chosen are IOC, FOK and Maker (Post Only). When the order book cannot meet with the corresponding conditions, the system will cancel the orders automatically:</p>

<p>Post_only: If the order placed is filled with an existing order on the order book immediately, the order will be cancelled to ensure the user is always a maker.</p>

<p>IOC order: If the order cannot be filled immediately, the unfilled part will be cancelled at once;</p>

<p>FOK order: If the order cannot be filled in its entirety, it will be wholly cancelled. No partial fulfillments are allowed.</p>
<h3 id="q21-how-to-query-the-maximum-amount-cont-available-to-open-by-using-users-current-assets">Q21: How to query the maximum amount (cont) available to open by using users’ current assets?</h3>
<p>At present, we do not have an interface by which users can directly query the maximum amount (cont) available to open by using users’ the current asset.</p>
<h3 id="q22-are-the-order_id-and-order_id_str-the-same">Q22: Are the “order_id” and “order_id_str” the same?</h3>
<p>The “order_id_str” is the string format of “order_id”, whose values are the same.</p>

<p>For the “order_id” with 18 bits, the “JSON.parse” in “nodejs” and “javascript” will be “int” by default, and mistakes will occur when analyzing. Thus, we advise using “order_id_str”.</p>
<h3 id="q23-how-to-get-the-active-buying-selling-quantity-in-transaction-data">Q23: How to get the active buying/selling quantity in transaction data?</h3>
<p>Users can get the data via “Query The Last Trade of a Contract” (/swap-ex/market/trade) interface or by subscribing "sub": "market.$contract_code.trade.detail", thereinto</p>

<p>Amount refers to the trading volume (cont), which is the sum of the buying/selling volume; </p>

<p>Direction refers to the active trading direction.</p>
<h3 id="q24-the-interval-between-from-and-to-is-2000-period-when-acquiring-kline-data-then-why-the-data-obtained-is">Q24: The interval between “from” and “to” is “2000*period” when acquiring KLine data, then why the data obtained is []?</h3>
<p>When acquiring the Kline data, the two time points “from” and “to” are contained, therefore it includes 2001 pieces of data. However, this exceeds the maximum limit 2000. Therefore, the system will return [].</p>

<p>Besides, the returned data will be [] as well if the interval between “from” and “to” exceeds 2 years.</p>
<h3 id="q25-how-to-get-the-latest-price">Q25: How to get the latest price?</h3>
<p>There are two methods to get the latest price:</p>

<p>a. Invoking the “Get KLine Data(swap-ex/market/history/kline)” interface and filling in any “period”, the “close” of the last data in return data will be the latest price;</p>

<p>b. Invoking the “Query The Last Trade of a Contract(swap-ex/market/trade)” interface, the returned “price” will be the latest price.</p>
<h3 id="q26-how-to-get-the-latest-index-price">Q26: How to get the latest index price?</h3>
<p>There are two methods to get the latest index price:</p>

<p>a.  Calling the “Get Contract Index Price Information” interface (/swap-api/v1/swap_index), the returned “index_price” will be the latest index price.</p>

<p>b.  Calling the “Subscribe Index Kline Data” websocket (market.$contract_code.index.$period), the “close” of the last Kline data in returned data will be the latest index price.</p>
<h3 id="q27-will-api-upgrade-affect-the-operation-of-the-program">Q27: Will API upgrade affect the operation of the program?</h3>
<p>In general, API upgrade will partly influence the ws disconnection. To avoid this, you can set up a ws-reconnect mechanism in advance; Please subscribe to the upgrade announcements for more details:</p>

<p>Coin-margined futures: https://status-dm.huobigroup.com/</p>

<p>Coin-margined swaps: https://status-swap.huobigroup.com/</p>

<p>USDT-margined swaps: https://status-linear-swap.huobigroup.com/</p>
<h3 id="q28-what-does-mean-the-margin_balance-in-query-user-s-account-information-interface-api-v1-contract_account_info">Q28:  What does mean the “margin_balance” in “Query User’s Account Information” interface (api/v1/contract_account_info)?</h3>
<p>”margin_balance” refers to the account equity</p>

<ol>
<li><p>margin_balance = margin_position + margin_frozen + margin_available</p></li>
<li><p>margin_balance = margin_static + profit_unreal</p></li>
<li><p>margin_balance = Account balance + profit_real + profit_unreal</p></li>
</ol>

<p>Note: Account balance = margin_static - profit_real, there is only margin_static in the return data of api interface</p>

<p>Each of the three calculation methods above can get the margin_balance</p>
<h3 id="q29-is-the-risk_rate-margin-rate-in-query-user-s-account-information-interface-swap-api-v1-swap_account_info-the-same-as-the-margin-rate-on-web">Q29: Is the “risk_rate” (margin rate) in “Query User’s Account Information” interface (/swap-api/v1/swap_account_info) the same as the margin rate on WEB?</h3>
<p>Yes, it is</p>

<p>When the “risk_rate” is less than or equal to 0, the position will be liquidated.</p>
<h2 id="error-codes">Error Codes</h2><h3 id="q1-what-is-the-reason-for-1030-error-code">Q1: What is the reason for 1030 error code?</h3>
<p>If you encounter errors such as {"status":"error","err_code":1030,"err_msg":"Abnormal service. Please try again later.","ts":1588093883199},indicating that your input request parameter is not correct, please print your request body and complete URL parameters, and please check the corresponding API document interface one by one.The common example is that the volume must be an integer. </p>
<h3 id="q2-what-is-the-reason-for-1048-error-code">Q2: What is the reason for 1048 error code?</h3>
<p>If you encounter errors such as {'index': 1, 'err_code': 1048, 'err_msg': 'Insufficient close amount available.'}, indicating that your available position is not enough.You need to query the api swap-api/v1/swap_position_info to get your available position.</p>

<ol>
<li><p>Check whether the amount (cont) of position-closing order exceeds the limit? (When there is limit order for closing a position, the quantity that available to be closed will be occupied; hence we kindly remind you to cancel these orders and try again.)</p></li>
<li><p>Check whether direction and offset are wrong as follows:</p></li>
</ol>

<p>close long: sell to close a long position (direction: sell; offset: close);</p>

<p>close short: buy to close a short position (direction: buy; offset: close);</p>

<p>Only “direction” need to be uploaded when placing a flash close order (close long: sell; close short: buy). </p>

<ol>
<li>The pending take-profit and stop-loss (tp/sl) orders and trigger orders will not occupy the quantity of the position.</li>
</ol>
<h3 id="q3-what-is-the-reason-for-1032-error-code">Q3: What is the reason for 1032 error code?</h3>
<p>1032 means that your request exceeds the ratelimit. The coin margined swap, future, option swap and USDT margined swap limit the rate separately. Please check the ratelimit in the api ratelimit instructions, and you can print the current ratelimit in the header of the API response to check whether the ratelimit is exceeded. It is recommended to increase the request interval delay to avoid exceeding the ratelimit.</p>
<h2 id="how-to-solve-problems-more-effectively">How to solve problems more effectively?</h2>
<p>When you report an API error, you need to attach your request URL, the original complete body of the request and the complete request URL parameters, and the original complete log of the server's response. If it is a websocket subscription, you need to provide the address of the subscription, the topic of the subscription, and the original complete log pushed by the server.</p>

<p>If it is an order-related issue, use the API order query interface swap-api/ v1/swap_order_info to keep the complete log returned and provide your UID and order number.</p>
<h1 id="swap-market-data-interface">Swap Market Data interface</h1><h2 id="query-swap-info">Query Swap Info</h2><h3 id="example">Example</h3>
<ul>
<li>GET  <code>/swap-api/v1/swap_contract_info</code></li>
</ul>
<pre class="highlight shell tab-shell" style=""><code>curl <span class="s2">"https://api.hbdm.com/swap-api/v1/swap_contract_info"</span>      
</code></pre><h3 id="request-parameter">Request Parameter</h3>
<table><thead>
<tr>
<th>Parameter Name</th>
<th>Type</th>
<th>Mandatory</th>
<th>Description</th>
</tr>
</thead><tbody>
<tr>
<td>contract_code</td>
<td>string</td>
<td>false</td>
<td>Case-insenstive.such as "BTC-USD". All swaps default.</td>
</tr>
</tbody></table>

<blockquote>
<p>Response</p>
</blockquote>
<pre class="highlight json tab-json"><code><span class="w">
</span><span class="p">{</span><span class="w">
    </span><span class="s2">"status"</span><span class="p">:</span><span class="w"> </span><span class="s2">"ok"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"data"</span><span class="p">:</span><span class="w"> </span><span class="p">[</span><span class="w">
        </span><span class="p">{</span><span class="w">
            </span><span class="s2">"symbol"</span><span class="p">:</span><span class="w"> </span><span class="s2">"BTC"</span><span class="p">,</span><span class="w">
            </span><span class="s2">"contract_code"</span><span class="p">:</span><span class="w"> </span><span class="s2">"BTC-USD"</span><span class="p">,</span><span class="w">
            </span><span class="s2">"contract_size"</span><span class="p">:</span><span class="w"> </span><span class="mf">100.000000000000000000</span><span class="p">,</span><span class="w">
            </span><span class="s2">"price_tick"</span><span class="p">:</span><span class="w"> </span><span class="mf">0.100000000000000000</span><span class="p">,</span><span class="w">
            </span><span class="s2">"create_date"</span><span class="p">:</span><span class="w"> </span><span class="s2">"20200325"</span><span class="p">,</span><span class="w">
            </span><span class="s2">"delivery_time"</span><span class="p">:</span><span class="w"> </span><span class="s2">""</span><span class="p">,</span><span class="w">
            </span><span class="s2">"contract_status"</span><span class="p">:</span><span class="w"> </span><span class="mi">1</span><span class="p">,</span><span class="w">
            </span><span class="s2">"settlement_date"</span><span class="p">:</span><span class="w"> </span><span class="s2">"1603872000000"</span><span class="w">
        </span><span class="p">}</span><span class="w">
    </span><span class="p">],</span><span class="w">
    </span><span class="s2">"ts"</span><span class="p">:</span><span class="w"> </span><span class="mi">1603851828069</span><span class="w">
</span><span class="p">}</span><span class="w">
</span></code></pre><h3 id="returning-parameter-3">Returning Parameter</h3>
<table><thead>
<tr>
<th>Parameter Name</th>
<th>Mandatory</th>
<th>Type</th>
<th>Description</th>
<th>Value Range</th>
</tr>
</thead><tbody>
<tr>
<td>status</td>
<td>true</td>
<td>string</td>
<td>Request Processing Result</td>
<td>"ok" , "error"</td>
</tr>
<tr>
<td>data &lt;list&gt;</td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr>
<td>symbol</td>
<td>true</td>
<td>string</td>
<td>symbol</td>
<td>"BTC","ETH"...</td>
</tr>
<tr>
<td>contract_code</td>
<td>true</td>
<td>string</td>
<td>Contract Code</td>
<td>"BTC-USD" ...</td>
</tr>
<tr>
<td>contract_size</td>
<td>true</td>
<td>decimal</td>
<td>Contract Value (USD of one contract)</td>
<td>10, 100...</td>
</tr>
<tr>
<td>price_tick</td>
<td>true</td>
<td>decimal</td>
<td>Minimum Variation of Contract Price</td>
<td>0.001, 0.01...</td>
</tr>
<tr>
<td>settlement_date</td>
<td>true</td>
<td>string</td>
<td>Settlement  Date</td>
<td>eg "1490759594752"</td>
</tr>
<tr>
<td>create_date</td>
<td>true</td>
<td>string</td>
<td>Listing Date</td>
<td>eg "20190808"</td>
</tr>
<tr>
<td>delivery_time</td>
<td>true</td>
<td>string</td>
<td>delivery time（When the contract does not need to be delivered, the field value is an empty string），millesecond timestamp</td>
<td></td>
</tr>
<tr>
<td>contract_status</td>
<td>true</td>
<td>int</td>
<td>Contract Status</td>
<td>0: Delisting,1: Listing,2: Pending Listing,3: Suspension,4: Suspending of Listing,5: In Settlement,6: Delivering,7: Settlement Completed,8: Delivered</td>
</tr>
<tr>
<td>&lt;/list&gt;</td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr>
<td>ts</td>
<td>true</td>
<td>long</td>
<td>Time of Respond Generation，Unit：Millisecond</td>
<td></td>
</tr>
</tbody></table>
<h2 id="query-swap-index-price-information">Query Swap Index Price Information</h2><h3 id="example-2">Example</h3>
<ul>
<li>GET <code>/swap-api/v1/swap_index</code> </li>
</ul>
<pre class="highlight shell tab-shell" style=""><code>curl <span class="s2">"https://api.hbdm.com/swap-api/v1/swap_index?contract_code=BTC-USD"</span>
</code></pre><h3 id="request-parameter-2">Request Parameter</h3>
<table><thead>
<tr>
<th>Parameter Name</th>
<th>Parameter Type</th>
<th>Mandatory</th>
<th>Desc</th>
</tr>
</thead><tbody>
<tr>
<td>contract_code</td>
<td>string</td>
<td>false</td>
<td>Case-insenstive."BTC-USD","ETH-USD"...</td>
</tr>
</tbody></table>

<blockquote>
<p>Response</p>
</blockquote>
<pre class="highlight json tab-json"><code><span class="w">
</span><span class="p">{</span><span class="w">
    </span><span class="s2">"status"</span><span class="p">:</span><span class="w"> </span><span class="s2">"ok"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"data"</span><span class="p">:</span><span class="w"> </span><span class="p">[</span><span class="w">
        </span><span class="p">{</span><span class="w">
            </span><span class="s2">"index_price"</span><span class="p">:</span><span class="w"> </span><span class="mf">13764.072500000000000000</span><span class="p">,</span><span class="w">
            </span><span class="s2">"index_ts"</span><span class="p">:</span><span class="w"> </span><span class="mi">1603851876012</span><span class="p">,</span><span class="w">
            </span><span class="s2">"contract_code"</span><span class="p">:</span><span class="w"> </span><span class="s2">"BTC-USD"</span><span class="w">
        </span><span class="p">}</span><span class="w">
    </span><span class="p">],</span><span class="w">
    </span><span class="s2">"ts"</span><span class="p">:</span><span class="w"> </span><span class="mi">1603851883506</span><span class="w">
</span><span class="p">}</span><span class="w">
</span></code></pre><h3 id="returning-parameter-4">Returning Parameter</h3>
<table><thead>
<tr>
<th>Parameter Name</th>
<th>Mandatory</th>
<th>Type</th>
<th>Desc</th>
<th>Value Range</th>
</tr>
</thead><tbody>
<tr>
<td>status</td>
<td>true</td>
<td>string</td>
<td>Request Processing Result</td>
<td>"ok" , "error"</td>
</tr>
<tr>
<td>data&lt;list&gt;</td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr>
<td>contract_code</td>
<td>true</td>
<td>string</td>
<td>contract_code</td>
<td>"BTC-USD","ETH-USD"...</td>
</tr>
<tr>
<td>index_price</td>
<td>true</td>
<td>decimal</td>
<td>Index Price</td>
<td></td>
</tr>
<tr>
<td>index_ts</td>
<td>true</td>
<td>Long</td>
<td>Index time</td>
<td></td>
</tr>
<tr>
<td>&lt;/list&gt;</td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr>
<td>ts</td>
<td>true</td>
<td>long</td>
<td>Time of Respond Generation，Unit：Millisecond</td>
<td></td>
</tr>
</tbody></table>
<h2 id="query-swap-price-limitation">Query Swap Price Limitation</h2><h3 id="example-3">Example</h3>
<ul>
<li>GET <code>/swap-api/v1/swap_price_limit</code> </li>
</ul>
<pre class="highlight shell tab-shell" style=""><code>curl <span class="s2">"https://api.hbdm.com/swap-api/v1/swap_price_limit?contract_code=BTC-USD
</span></code></pre><h3 id="request-parameter-3">Request Parameter</h3>
<table><thead>
<tr>
<th>Parameter Name</th>
<th>Parameter Type</th>
<th>Mandatory</th>
<th>Desc</th>
</tr>
</thead><tbody>
<tr>
<td>contract_code</td>
<td>string</td>
<td>false</td>
<td>Case-insenstive.such as:BTC-USD, All swaps default</td>
</tr>
</tbody></table>

<blockquote>
<p>Response</p>
</blockquote>
<pre class="highlight json tab-json"><code><span class="w">

</span><span class="p">{</span><span class="w">
    </span><span class="s2">"status"</span><span class="p">:</span><span class="w"> </span><span class="s2">"ok"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"data"</span><span class="p">:</span><span class="w"> </span><span class="p">[</span><span class="w">
        </span><span class="p">{</span><span class="w">
            </span><span class="s2">"symbol"</span><span class="p">:</span><span class="w"> </span><span class="s2">"BTC"</span><span class="p">,</span><span class="w">
            </span><span class="s2">"contract_code"</span><span class="p">:</span><span class="w"> </span><span class="s2">"BTC-USD"</span><span class="p">,</span><span class="w">
            </span><span class="s2">"high_limit"</span><span class="p">:</span><span class="w"> </span><span class="mf">14313.100000000000000000000000000000000000</span><span class="p">,</span><span class="w">
            </span><span class="s2">"low_limit"</span><span class="p">:</span><span class="w"> </span><span class="mf">13212.200000000000000000000000000000000000</span><span class="w">
        </span><span class="p">}</span><span class="w">
    </span><span class="p">],</span><span class="w">
    </span><span class="s2">"ts"</span><span class="p">:</span><span class="w"> </span><span class="mi">1603851945000</span><span class="w">
</span><span class="p">}</span><span class="w">
</span></code></pre><h3 id="returning-parameter-5">Returning Parameter</h3>
<table><thead>
<tr>
<th>Parameter Name</th>
<th>Mandatory</th>
<th>Type</th>
<th>Desc</th>
<th>Value Range</th>
</tr>
</thead><tbody>
<tr>
<td>status</td>
<td>true</td>
<td>string</td>
<td>Request Processing Result</td>
<td>"ok" ,"error"</td>
</tr>
<tr>
<td>&lt;data&gt;</td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr>
<td>symbol</td>
<td>true</td>
<td>string</td>
<td>Variety code</td>
<td>"BTC","ETH" ...</td>
</tr>
<tr>
<td>high_limit</td>
<td>true</td>
<td>decimal</td>
<td>Highest Buying Price</td>
<td></td>
</tr>
<tr>
<td>low_limit</td>
<td>true</td>
<td>decimal</td>
<td>Lowest Selling Price</td>
<td></td>
</tr>
<tr>
<td>contract_code</td>
<td>true</td>
<td>string</td>
<td>Contract Code</td>
<td>eg "BTC-USD"  ...</td>
</tr>
<tr>
<td>&lt;data&gt;</td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr>
<td>ts</td>
<td>true</td>
<td>long</td>
<td>Time of Respond Generation, Unit: Millisecond</td>
<td></td>
</tr>
</tbody></table>
<h2 id="get-swap-open-interest-information">Get Swap Open Interest Information</h2><h3 id="example-4">Example</h3>
<ul>
<li>GET <code>/swap-api/v1/swap_open_interest</code> </li>
</ul>
<pre class="highlight shell tab-shell" style=""><code>curl <span class="s2">"https://api.hbdm.com/swap-api/v1/swap_open_interest?contract_code=BTC-USD"</span>
</code></pre><h3 id="request-parameter-4">Request Parameter</h3>
<table><thead>
<tr>
<th>Parameter Name</th>
<th>Parameter Type</th>
<th>Mandatory</th>
<th>Desc</th>
</tr>
</thead><tbody>
<tr>
<td>contract_code</td>
<td>string</td>
<td>false</td>
<td>Case-insenstive.such as BTC-USD. ALL contracts by default.</td>
</tr>
</tbody></table>

<blockquote>
<p>Response:</p>
</blockquote>
<pre class="highlight json tab-json"><code><span class="w">
</span><span class="p">{</span><span class="w">
    </span><span class="s2">"status"</span><span class="p">:</span><span class="w"> </span><span class="s2">"ok"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"data"</span><span class="p">:</span><span class="w"> </span><span class="p">[</span><span class="w">
        </span><span class="p">{</span><span class="w">
            </span><span class="s2">"volume"</span><span class="p">:</span><span class="w"> </span><span class="mf">2369902.000000000000000000</span><span class="p">,</span><span class="w">
            </span><span class="s2">"amount"</span><span class="p">:</span><span class="w"> </span><span class="mf">17225.879137652822398930</span><span class="p">,</span><span class="w">
            </span><span class="s2">"symbol"</span><span class="p">:</span><span class="w"> </span><span class="s2">"BTC"</span><span class="p">,</span><span class="w">
            </span><span class="s2">"contract_code"</span><span class="p">:</span><span class="w"> </span><span class="s2">"BTC-USD"</span><span class="p">,</span><span class="w">
            </span><span class="s2">"trade_amount"</span><span class="p">:</span><span class="w"> </span><span class="mf">1.42</span><span class="p">,</span><span class="w">
            </span><span class="s2">"trade_volume"</span><span class="p">:</span><span class="w"> </span><span class="mi">142</span><span class="p">,</span><span class="w">
            </span><span class="s2">"trade_turnover"</span><span class="p">:</span><span class="w"> </span><span class="mf">7.847622</span><span class="w">
        </span><span class="p">}</span><span class="w">
    </span><span class="p">],</span><span class="w">
    </span><span class="s2">"ts"</span><span class="p">:</span><span class="w"> </span><span class="mi">1603852005954</span><span class="w">
</span><span class="p">}</span><span class="w">
</span></code></pre><h3 id="returning-parameter-6">Returning Parameter</h3>
<table><thead>
<tr>
<th>Parameter Name</th>
<th>Mandatory</th>
<th>Type</th>
<th>Desc</th>
<th>Value Range</th>
</tr>
</thead><tbody>
<tr>
<td>status</td>
<td>true</td>
<td>string</td>
<td>Request Processing Result</td>
<td>"ok" , "error"</td>
</tr>
<tr>
<td>data &lt;list&gt;</td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr>
<td>symbol</td>
<td>true</td>
<td>string</td>
<td>Variety code</td>
<td>"BTC", "ETH" ...</td>
</tr>
<tr>
<td>volume</td>
<td>true</td>
<td>decimal</td>
<td>Position quantity(volume). Single side</td>
<td></td>
</tr>
<tr>
<td>amount</td>
<td>true</td>
<td>decimal</td>
<td>Position quantity(Currency). Single side</td>
<td></td>
</tr>
<tr>
<td>contract_code</td>
<td>true</td>
<td>string</td>
<td>Contract Code</td>
<td>eg "BTC-USD"   ...</td>
</tr>
<tr>
<td>trade_amount</td>
<td>true</td>
<td>decimal</td>
<td>trading volume within the last 24 hours (coin). Sum of both buy and sell sides</td>
<td></td>
</tr>
<tr>
<td>trade_volume</td>
<td>true</td>
<td>decimal</td>
<td>trading volume within the last 24 hours (cont). Sum of both buy and sell sides</td>
<td></td>
</tr>
<tr>
<td>trade_turnover</td>
<td>true</td>
<td>decimal</td>
<td>trading amount within the last 24 hours. Sum of both buy and sell sides</td>
<td></td>
</tr>
<tr>
<td>&lt;/list&gt;</td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr>
<td>ts</td>
<td>true</td>
<td>long</td>
<td>Time of Respond Generation, Unit: Millisecond</td>
<td></td>
</tr>
</tbody></table>
<h2 id="get-market-depth">Get Market Depth</h2><h3 id="example-5">Example</h3>
<ul>
<li>GET <code>/swap-ex/market/depth</code> </li>
</ul>
<pre class="highlight shell tab-shell" style=""><code>curl <span class="s2">"https://api.hbdm.com/swap-ex/market/depth?contract_code=BTC-USD&amp;type=step5"</span>
</code></pre><h3 id="request-parameter-5">Request Parameter</h3>
<table><thead>
<tr>
<th>Parameter Name</th>
<th>Parameter Type</th>
<th>Mandatory</th>
<th>Desc</th>
</tr>
</thead><tbody>
<tr>
<td>contract_code</td>
<td>string</td>
<td>true</td>
<td>Case-Insenstive.Both uppercase and lowercase are supported..e.g. "BTC-USD"</td>
</tr>
<tr>
<td>type</td>
<td>string</td>
<td>true</td>
<td>Get depth data within step 150, use step0, step1, step2, step3, step4, step5, step14, step15（merged depth data 0-5,14-15）；when step is 0，depth data will not be merged; Get depth data within step 20, use step6, step7, step8, step9, step10, step11, step12, step13(merged depth data 7-13); when step is 6, depth data will not be merged.</td>
</tr>
</tbody></table>

<blockquote>
<p>Response:</p>
</blockquote>
<pre class="highlight json tab-json"><code><span class="w">
</span><span class="p">{</span><span class="w">
    </span><span class="s2">"ch"</span><span class="p">:</span><span class="w"> </span><span class="s2">"market.BTC-USD.depth.step6"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"status"</span><span class="p">:</span><span class="w"> </span><span class="s2">"ok"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"ts"</span><span class="p">:</span><span class="w"> </span><span class="mi">1603852132212</span><span class="p">,</span><span class="w">
    </span><span class="s2">"tick"</span><span class="p">:</span><span class="w"> </span><span class="p">{</span><span class="w">
        </span><span class="s2">"mrid"</span><span class="p">:</span><span class="w"> </span><span class="mi">50950394258</span><span class="p">,</span><span class="w">
        </span><span class="s2">"id"</span><span class="p">:</span><span class="w"> </span><span class="mi">1603852132</span><span class="p">,</span><span class="w">
        </span><span class="s2">"bids"</span><span class="p">:</span><span class="w"> </span><span class="p">[</span><span class="w">
            </span><span class="p">[</span><span class="w">
                </span><span class="mf">13762.2</span><span class="p">,</span><span class="w">
                </span><span class="mi">22198</span><span class="w">
            </span><span class="p">],</span><span class="w">
            </span><span class="p">[</span><span class="w">
                </span><span class="mf">13762.1</span><span class="p">,</span><span class="w">
                </span><span class="mi">566</span><span class="w">
            </span><span class="p">]</span><span class="w">
        </span><span class="p">],</span><span class="w">
        </span><span class="s2">"asks"</span><span class="p">:</span><span class="w"> </span><span class="p">[</span><span class="w">
            </span><span class="p">[</span><span class="w">
                </span><span class="mf">13762.3</span><span class="p">,</span><span class="w">
                </span><span class="mi">4193</span><span class="w">
            </span><span class="p">],</span><span class="w">
            </span><span class="p">[</span><span class="w">
                </span><span class="mf">13762.4</span><span class="p">,</span><span class="w">
                </span><span class="mi">2</span><span class="w">
            </span><span class="p">]</span><span class="w">
        </span><span class="p">],</span><span class="w">
        </span><span class="s2">"ts"</span><span class="p">:</span><span class="w"> </span><span class="mi">1603852132152</span><span class="p">,</span><span class="w">
        </span><span class="s2">"version"</span><span class="p">:</span><span class="w"> </span><span class="mi">1603852132</span><span class="p">,</span><span class="w">
        </span><span class="s2">"ch"</span><span class="p">:</span><span class="w"> </span><span class="s2">"market.BTC-USD.depth.step6"</span><span class="w">
    </span><span class="p">}</span><span class="w">
</span><span class="p">}</span><span class="w">
</span></code></pre><h3 id="returning-parameter-7">Returning Parameter</h3>
<table><thead>
<tr>
<th>Parameter Name</th>
<th>Mandatory</th>
<th>Data Type</th>
<th>Desc</th>
<th>Value Range</th>
</tr>
</thead><tbody>
<tr>
<td>ch</td>
<td>true</td>
<td>string</td>
<td>Data belonged channel，Format： market.period</td>
<td></td>
</tr>
<tr>
<td>status</td>
<td>true</td>
<td>string</td>
<td>Request Processing Result</td>
<td>"ok" , "error"</td>
</tr>
<tr>
<td>ts</td>
<td>true</td>
<td>long</td>
<td>Time of Respond Generation，Unit：Millisecond</td>
<td></td>
</tr>
<tr>
<td>&lt;tick&gt;</td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr>
<td>mrid</td>
<td>true</td>
<td>string</td>
<td>Order ID</td>
<td></td>
</tr>
<tr>
<td>id</td>
<td>true</td>
<td>string</td>
<td>tick ID</td>
<td></td>
</tr>
<tr>
<td>asks</td>
<td>true</td>
<td>object</td>
<td>Sell,[price(Ask price), vol(Ask orders (cont.) )], price in ascending sequence</td>
<td></td>
</tr>
<tr>
<td>bids</td>
<td>true</td>
<td>object</td>
<td>Buy,[price(Bid price), vol(Bid orders(Cont.))], Price in descending sequence</td>
<td></td>
</tr>
<tr>
<td>ts</td>
<td>true</td>
<td>long</td>
<td>Time of Respond Generation, Unit: Millisecond</td>
<td></td>
</tr>
<tr>
<td>version</td>
<td>true</td>
<td>long</td>
<td>version ID</td>
<td></td>
</tr>
<tr>
<td>ch</td>
<td>true</td>
<td>string</td>
<td>Data channel, Format： market.period</td>
<td></td>
</tr>
<tr>
<td>&lt;/tick&gt;</td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
</tbody></table>
<h2 id="get-kline-data">Get KLine Data</h2><h3 id="example-6">Example</h3>
<ul>
<li>GET <code>/swap-ex/market/history/kline</code> </li>
</ul>
<pre class="highlight shell tab-shell" style=""><code>curl <span class="s2">"https://api.hbdm.com/swap-ex/market/history/kline?period=1min&amp;size=200&amp;contract_code=BTC-USD"</span>
</code></pre><h3 id="request-parameter-6">Request Parameter</h3>
<table><thead>
<tr>
<th>Parameter Name</th>
<th>Mandatory</th>
<th>Type</th>
<th>Desc</th>
<th>Default</th>
<th>Value Range</th>
</tr>
</thead><tbody>
<tr>
<td>contract_code</td>
<td>true</td>
<td>string</td>
<td>Case-Insenstive.Both uppercase and lowercase are supported..e.g. "BTC-USD"</td>
<td></td>
<td></td>
</tr>
<tr>
<td>period</td>
<td>true</td>
<td>string</td>
<td>KLine Type</td>
<td></td>
<td>1min, 5min, 15min, 30min, 60min, 1hour,4hour,1day, 1mon</td>
</tr>
<tr>
<td>size</td>
<td>false</td>
<td>int</td>
<td>Acquisition Quantity</td>
<td>150</td>
<td>[1,2000]</td>
</tr>
<tr>
<td>from</td>
<td>false</td>
<td>long</td>
<td>start timestamp seconds.</td>
<td></td>
<td></td>
</tr>
<tr>
<td>to</td>
<td>false</td>
<td>long</td>
<td>end timestamp seconds</td>
<td></td>
<td></td>
</tr>
</tbody></table>
<h3 id="note-2">Note</h3>
<ul>
<li>Either <code>size</code> field or <code>from</code> and <code>to</code> fields need to be filled.</li>
<li>If <code>size</code> field and <code>from</code>/<code>to</code> fields are not filled, It will return error messages.</li>
<li>If <code>from</code> field is filled, <code>to</code> field need to filled too.</li>
<li>The api can mostly return the klines of last two years.</li>
<li>If <code>from</code> <code>to</code> <code>size</code> are all filled,'from' and 'to' will be ignored.</li>
</ul>

<blockquote>
<p>Data Illustration：</p>
</blockquote>
<pre class="highlight plaintext"><code>"data": [
  {
        "id": KLine id,
        "vol": Transaction Volume(amount),
        "count": transaction count
        "open": opening Price
        "close": Closing Price, when the Kline is the latest one，it means the latest price
        "low": Lowest price
        "high": highest price
        "amount": transaction volume(currency), sum(every transaction volume(amount)*every contract value/transaction price for this contract)
   }
]
</code></pre>
<blockquote>
<p>Response:</p>
</blockquote>
<pre class="highlight json tab-json"><code><span class="w">
</span><span class="p">{</span><span class="w">
    </span><span class="s2">"ch"</span><span class="p">:</span><span class="w"> </span><span class="s2">"market.BTC-USD.kline.5min"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"data"</span><span class="p">:</span><span class="w"> </span><span class="p">[</span><span class="w">
        </span><span class="p">{</span><span class="w">
            </span><span class="s2">"amount"</span><span class="p">:</span><span class="w"> </span><span class="mf">876.9369459997886</span><span class="p">,</span><span class="w">
            </span><span class="s2">"close"</span><span class="p">:</span><span class="w"> </span><span class="mf">13782.1</span><span class="p">,</span><span class="w">
            </span><span class="s2">"count"</span><span class="p">:</span><span class="w"> </span><span class="mi">1357</span><span class="p">,</span><span class="w">
            </span><span class="s2">"high"</span><span class="p">:</span><span class="w"> </span><span class="mf">13782.2</span><span class="p">,</span><span class="w">
            </span><span class="s2">"id"</span><span class="p">:</span><span class="w"> </span><span class="mi">1603851900</span><span class="p">,</span><span class="w">
            </span><span class="s2">"low"</span><span class="p">:</span><span class="w"> </span><span class="mf">13755.8</span><span class="p">,</span><span class="w">
            </span><span class="s2">"open"</span><span class="p">:</span><span class="w"> </span><span class="mf">13764.7</span><span class="p">,</span><span class="w">
            </span><span class="s2">"vol"</span><span class="p">:</span><span class="w"> </span><span class="mi">120706</span><span class="w">
        </span><span class="p">},</span><span class="w">
        </span><span class="p">{</span><span class="w">
            </span><span class="s2">"amount"</span><span class="p">:</span><span class="w"> </span><span class="mf">921.6695838405225</span><span class="p">,</span><span class="w">
            </span><span class="s2">"close"</span><span class="p">:</span><span class="w"> </span><span class="mi">13779</span><span class="p">,</span><span class="w">
            </span><span class="s2">"count"</span><span class="p">:</span><span class="w"> </span><span class="mi">1111</span><span class="p">,</span><span class="w">
            </span><span class="s2">"high"</span><span class="p">:</span><span class="w"> </span><span class="mf">13787.6</span><span class="p">,</span><span class="w">
            </span><span class="s2">"id"</span><span class="p">:</span><span class="w"> </span><span class="mi">1603852200</span><span class="p">,</span><span class="w">
            </span><span class="s2">"low"</span><span class="p">:</span><span class="w"> </span><span class="mf">13777.5</span><span class="p">,</span><span class="w">
            </span><span class="s2">"open"</span><span class="p">:</span><span class="w"> </span><span class="mf">13782.1</span><span class="p">,</span><span class="w">
            </span><span class="s2">"vol"</span><span class="p">:</span><span class="w"> </span><span class="mi">127036</span><span class="w">
        </span><span class="p">}</span><span class="w">
    </span><span class="p">],</span><span class="w">
    </span><span class="s2">"status"</span><span class="p">:</span><span class="w"> </span><span class="s2">"ok"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"ts"</span><span class="p">:</span><span class="w"> </span><span class="mi">1603852355339</span><span class="w">
</span><span class="p">}</span><span class="w">
</span></code></pre><h3 id="returning-parameter-8">Returning Parameter</h3>
<table><thead>
<tr>
<th>Parameter Name</th>
<th>Mandatory</th>
<th>Data Type</th>
<th>Desc</th>
<th>Value Range</th>
</tr>
</thead><tbody>
<tr>
<td>ch</td>
<td>true</td>
<td>string</td>
<td>Data belonged channel，Format： market.period</td>
<td></td>
</tr>
<tr>
<td>status</td>
<td>true</td>
<td>string</td>
<td>Request Processing Result</td>
<td>"ok" , "error"</td>
</tr>
<tr>
<td>ts</td>
<td>true</td>
<td>long</td>
<td>Time of Respond Generation, Unit: Millisecond</td>
<td></td>
</tr>
<tr>
<td>&lt;list&gt;(attr name: data)</td>
<td></td>
<td>kline data</td>
<td></td>
<td></td>
</tr>
<tr>
<td>id</td>
<td>true</td>
<td>long</td>
<td>kline id,the same as kline timestamp, kline start timestamp</td>
<td></td>
</tr>
<tr>
<td>vol</td>
<td>true</td>
<td>decimal</td>
<td>Trade Volume(Cont.). Sum of both buy and sell sides</td>
<td></td>
</tr>
<tr>
<td>count</td>
<td>true</td>
<td>decimal</td>
<td>Order Quantity. Sum of both buy and sell sides</td>
<td></td>
</tr>
<tr>
<td>open</td>
<td>true</td>
<td>decimal</td>
<td>Opening Price</td>
<td></td>
</tr>
<tr>
<td>close</td>
<td>true</td>
<td>decimal</td>
<td>Closing Price,  the price in the last kline is the latest order price</td>
<td></td>
</tr>
<tr>
<td>low</td>
<td>true</td>
<td>decimal</td>
<td>Low</td>
<td></td>
</tr>
<tr>
<td>high</td>
<td>true</td>
<td>decimal</td>
<td>High</td>
<td></td>
</tr>
<tr>
<td>amount</td>
<td>true</td>
<td>decimal</td>
<td>Trade Amount(Coin),  trade amount(coin)=sum(order quantity of a single order * face value of the coin/order price). Sum of both buy and sell sides</td>
<td></td>
</tr>
<tr>
<td>&lt;/list&gt;</td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
</tbody></table>
<h2 id="get-kline-data-of-mark-price">Get Kline Data of Mark Price</h2>
<ul>
<li>GET <code>/index/market/history/swap_mark_price_kline</code></li>
</ul>
<h3 id="request-parameter-7">Request Parameter：</h3>
<table><thead>
<tr>
<th>Parameter Name</th>
<th>Mandatory</th>
<th>Type</th>
<th>Description</th>
<th>Default Value</th>
<th>Value Range**</th>
</tr>
</thead><tbody>
<tr>
<td>contract_code</td>
<td>true</td>
<td>string</td>
<td>contract code</td>
<td></td>
<td>"BTC-USD","ETH-USD"...</td>
</tr>
<tr>
<td>period</td>
<td>true</td>
<td>string</td>
<td>period type</td>
<td></td>
<td>1min, 5min, 15min, 30min, 60min,4hour,1day, 1week,1mon</td>
</tr>
<tr>
<td>size</td>
<td>true</td>
<td>int</td>
<td>size</td>
<td></td>
<td>[1,2000]</td>
</tr>
</tbody></table>
<h4 id="note-3">Note</h4>
<ul>
<li>At one time 2000 at most</li>
<li>The input parameters are not case sensitive and all support</li>
</ul>

<blockquote>
<p>Response：</p>
</blockquote>
<pre class="highlight json tab-json"><code><span class="p">{</span><span class="w">
    </span><span class="s2">"ch"</span><span class="p">:</span><span class="w"> </span><span class="s2">"market.BTC-USD.mark_price.5min"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"data"</span><span class="p">:</span><span class="w"> </span><span class="p">[</span><span class="w">
        </span><span class="p">{</span><span class="w">
            </span><span class="s2">"amount"</span><span class="p">:</span><span class="w"> </span><span class="s2">"0"</span><span class="p">,</span><span class="w">
            </span><span class="s2">"close"</span><span class="p">:</span><span class="w"> </span><span class="s2">"37127.6145"</span><span class="p">,</span><span class="w">
            </span><span class="s2">"count"</span><span class="p">:</span><span class="w"> </span><span class="s2">"0"</span><span class="p">,</span><span class="w">
            </span><span class="s2">"high"</span><span class="p">:</span><span class="w"> </span><span class="s2">"37213.4724"</span><span class="p">,</span><span class="w">
            </span><span class="s2">"id"</span><span class="p">:</span><span class="w"> </span><span class="mi">1611112800</span><span class="p">,</span><span class="w">
            </span><span class="s2">"low"</span><span class="p">:</span><span class="w"> </span><span class="s2">"37127.6145"</span><span class="p">,</span><span class="w">
            </span><span class="s2">"open"</span><span class="p">:</span><span class="w"> </span><span class="s2">"37200.3785"</span><span class="p">,</span><span class="w">
            </span><span class="s2">"trade_turnover"</span><span class="p">:</span><span class="w"> </span><span class="s2">"0"</span><span class="p">,</span><span class="w">
            </span><span class="s2">"vol"</span><span class="p">:</span><span class="w"> </span><span class="s2">"0"</span><span class="w">
        </span><span class="p">},</span><span class="w">
        </span><span class="p">{</span><span class="w">
            </span><span class="s2">"amount"</span><span class="p">:</span><span class="w"> </span><span class="s2">"0"</span><span class="p">,</span><span class="w">
            </span><span class="s2">"close"</span><span class="p">:</span><span class="w"> </span><span class="s2">"37200.1849"</span><span class="p">,</span><span class="w">
            </span><span class="s2">"count"</span><span class="p">:</span><span class="w"> </span><span class="s2">"0"</span><span class="p">,</span><span class="w">
            </span><span class="s2">"high"</span><span class="p">:</span><span class="w"> </span><span class="s2">"37249.2345"</span><span class="p">,</span><span class="w">
            </span><span class="s2">"id"</span><span class="p">:</span><span class="w"> </span><span class="mi">1611113100</span><span class="p">,</span><span class="w">
            </span><span class="s2">"low"</span><span class="p">:</span><span class="w"> </span><span class="s2">"37127.6145"</span><span class="p">,</span><span class="w">
            </span><span class="s2">"open"</span><span class="p">:</span><span class="w"> </span><span class="s2">"37127.6145"</span><span class="p">,</span><span class="w">
            </span><span class="s2">"trade_turnover"</span><span class="p">:</span><span class="w"> </span><span class="s2">"0"</span><span class="p">,</span><span class="w">
            </span><span class="s2">"vol"</span><span class="p">:</span><span class="w"> </span><span class="s2">"0"</span><span class="w">
        </span><span class="p">}</span><span class="w">
    </span><span class="p">],</span><span class="w">
    </span><span class="s2">"ts"</span><span class="p">:</span><span class="w"> </span><span class="mi">1611127713984</span><span class="w">
</span><span class="p">}</span><span class="w">
</span></code></pre><h3 id="returning-parameter-9">Returning Parameter：</h3>
<table><thead>
<tr>
<th>Parameter Name</th>
<th>Mandatory</th>
<th>Type</th>
<th>Description</th>
<th>Default Value</th>
<th>Value Range</th>
</tr>
</thead><tbody>
<tr>
<td>ch</td>
<td>true</td>
<td>string</td>
<td>channel, formation: market.period</td>
<td></td>
<td></td>
</tr>
<tr>
<td>&lt;data&gt;</td>
<td>true</td>
<td>object array</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr>
<td>id</td>
<td>true</td>
<td>long</td>
<td>id</td>
<td></td>
<td></td>
</tr>
<tr>
<td>vol</td>
<td>true</td>
<td>string</td>
<td>trade vol(cont), value is 0</td>
<td></td>
<td></td>
</tr>
<tr>
<td>count</td>
<td>true</td>
<td>string</td>
<td>trade count, value is 0</td>
<td></td>
<td></td>
</tr>
<tr>
<td>open</td>
<td>true</td>
<td>string</td>
<td>open price</td>
<td></td>
<td></td>
</tr>
<tr>
<td>close</td>
<td>true</td>
<td>string</td>
<td>close price</td>
<td></td>
<td></td>
</tr>
<tr>
<td>low</td>
<td>true</td>
<td>string</td>
<td>low price</td>
<td></td>
<td></td>
</tr>
<tr>
<td>high</td>
<td>true</td>
<td>string</td>
<td>hight price</td>
<td></td>
<td></td>
</tr>
<tr>
<td>amount</td>
<td>true</td>
<td>string</td>
<td>trade amount(coin), value is 0</td>
<td></td>
<td></td>
</tr>
<tr>
<td>trade_turnover</td>
<td>true</td>
<td>string</td>
<td>trade turnover, value is 0</td>
<td></td>
<td></td>
</tr>
<tr>
<td>&lt;/data&gt;</td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr>
<td>ts</td>
<td>true</td>
<td>long</td>
<td>Time of Respond Generation, Unit：Millisecond</td>
<td></td>
<td></td>
</tr>
</tbody></table>
<h2 id="get-market-data-overview">Get Market Data Overview</h2><h3 id="example-7">Example</h3>
<ul>
<li>GET <code>/swap-ex/market/detail/merged</code></li>
</ul>
<pre class="highlight shell tab-shell" style=""><code>curl <span class="s2">"https://api.hbdm.com/swap-ex/market/detail/merged?contract_code=BTC-USD"</span>
</code></pre><h3 id="request-parameter-8">Request Parameter</h3>
<table><thead>
<tr>
<th>Parameter Name</th>
<th>Mandatory</th>
<th>Type</th>
<th>Desc</th>
<th>Default</th>
<th>Value Range</th>
</tr>
</thead><tbody>
<tr>
<td>contract_code</td>
<td>true</td>
<td>string</td>
<td>Case-Insenstive.Both uppercase and lowercase are supported..e.g. "BTC-USD"</td>
<td></td>
<td></td>
</tr>
</tbody></table>

<blockquote>
<p>tick Illustration:</p>
</blockquote>
<pre class="highlight plaintext"><code>"tick": {
    "id": KLine id,
    "vol": transaction volume（contract）,
    "count": transaction count
    "open": opening price,
    "close": Closing Price, when the Kline is the latest one，it means the latest price
    "low": Lowest price
    "high": highest price
    "amount": transaction volume(currency), sum(every transaction volume(amount)*every contract value/transaction price for this contract)
    "bid": [price of buying one (amount)],
    "ask": [price of selling one (amount)]

  }
</code></pre>
<blockquote>
<p>Response:</p>
</blockquote>
<pre class="highlight json tab-json"><code><span class="w">

</span><span class="p">{</span><span class="w">
    </span><span class="s2">"ch"</span><span class="p">:</span><span class="w"> </span><span class="s2">"market.BTC-USD.detail.merged"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"status"</span><span class="p">:</span><span class="w"> </span><span class="s2">"ok"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"tick"</span><span class="p">:</span><span class="w"> </span><span class="p">{</span><span class="w">
        </span><span class="s2">"amount"</span><span class="p">:</span><span class="w"> </span><span class="s2">"358917.5563748616647638772009932561387079078"</span><span class="p">,</span><span class="w">
        </span><span class="s2">"ask"</span><span class="p">:</span><span class="w"> </span><span class="p">[</span><span class="w">
            </span><span class="mf">13780.3</span><span class="p">,</span><span class="w">
            </span><span class="mi">25907</span><span class="w">
        </span><span class="p">],</span><span class="w">
        </span><span class="s2">"bid"</span><span class="p">:</span><span class="w"> </span><span class="p">[</span><span class="w">
            </span><span class="mf">13780.2</span><span class="p">,</span><span class="w">
            </span><span class="mi">1455</span><span class="w">
        </span><span class="p">],</span><span class="w">
        </span><span class="s2">"close"</span><span class="p">:</span><span class="w"> </span><span class="s2">"13780.2"</span><span class="p">,</span><span class="w">
        </span><span class="s2">"count"</span><span class="p">:</span><span class="w"> </span><span class="mi">412778</span><span class="p">,</span><span class="w">
        </span><span class="s2">"high"</span><span class="p">:</span><span class="w"> </span><span class="s2">"13796.5"</span><span class="p">,</span><span class="w">
        </span><span class="s2">"id"</span><span class="p">:</span><span class="w"> </span><span class="mi">1603852483</span><span class="p">,</span><span class="w">
        </span><span class="s2">"low"</span><span class="p">:</span><span class="w"> </span><span class="s2">"13531.2"</span><span class="p">,</span><span class="w">
        </span><span class="s2">"open"</span><span class="p">:</span><span class="w"> </span><span class="s2">"13616.9"</span><span class="p">,</span><span class="w">
        </span><span class="s2">"ts"</span><span class="p">:</span><span class="w"> </span><span class="mi">1603852483765</span><span class="p">,</span><span class="w">
        </span><span class="s2">"vol"</span><span class="p">:</span><span class="w"> </span><span class="s2">"48357818"</span><span class="w">
    </span><span class="p">},</span><span class="w">
    </span><span class="s2">"ts"</span><span class="p">:</span><span class="w"> </span><span class="mi">1603852483765</span><span class="w">
</span><span class="p">}</span><span class="w">
</span></code></pre><h3 id="returning-parameter-10">Returning Parameter</h3>
<table><thead>
<tr>
<th>Parameter Name</th>
<th>Mandatory</th>
<th>Data Type</th>
<th>Desc</th>
<th>Value Range</th>
</tr>
</thead><tbody>
<tr>
<td>ch</td>
<td>true</td>
<td>string</td>
<td>Data belonged channel，format： market.$contract_code.detail.merged</td>
<td></td>
</tr>
<tr>
<td>status</td>
<td>true</td>
<td>string</td>
<td>Request Processing Result</td>
<td>"ok" , "error"</td>
</tr>
<tr>
<td>ts</td>
<td>true</td>
<td>long</td>
<td>Time of Respond Generation, Unit: Millisecond</td>
<td></td>
</tr>
<tr>
<td>&lt;tick&gt;</td>
<td></td>
<td></td>
<td>kline data (Start at 00:00(UTC+8) of the day)</td>
<td></td>
</tr>
<tr>
<td>id</td>
<td>true</td>
<td>long</td>
<td>kline id,the same as kline timestamp</td>
<td></td>
</tr>
<tr>
<td>vol</td>
<td>true</td>
<td>string</td>
<td>Trade Volume(Cont.). Sum of both buy and sell sides</td>
<td></td>
</tr>
<tr>
<td>count</td>
<td>true</td>
<td>decimal</td>
<td>Order Quantity. Sum of both buy and sell sides</td>
<td></td>
</tr>
<tr>
<td>open</td>
<td>true</td>
<td>string</td>
<td>Opening Price</td>
<td></td>
</tr>
<tr>
<td>close</td>
<td>true</td>
<td>string</td>
<td>Closing Price,  the price in the last kline is the latest order price</td>
<td></td>
</tr>
<tr>
<td>low</td>
<td>true</td>
<td>string</td>
<td>Low</td>
<td></td>
</tr>
<tr>
<td>high</td>
<td>true</td>
<td>string</td>
<td>High</td>
<td></td>
</tr>
<tr>
<td>amount</td>
<td>true</td>
<td>string</td>
<td>Trade Amount(Coin),  trade amount(coin)=sum(order quantity of a single order * face value of the coin/order price). Sum of both buy and sell sides</td>
<td></td>
</tr>
<tr>
<td>ask</td>
<td>true</td>
<td>object</td>
<td>Sell,[price(Ask price), vol(Ask orders (cont.) )], price in ascending sequence</td>
<td></td>
</tr>
<tr>
<td>bid</td>
<td>true</td>
<td>object</td>
<td>Buy,[price(Bid price), vol(Bid orders(Cont.))], Price in descending sequence</td>
<td></td>
</tr>
<tr>
<td>ts</td>
<td>true</td>
<td>long</td>
<td>Timestamp</td>
<td></td>
</tr>
<tr>
<td>&lt;/tick&gt;</td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
</tbody></table>
<h2 id="get-a-batch-of-market-data-overview">Get a Batch of Market Data Overview</h2>
<ul>
<li>GET <code>/swap-ex/market/detail/batch_merged</code></li>
</ul>
<h3 id="request-parameter-9">Request Parameter</h3>
<table><thead>
<tr>
<th>Parameter Name</th>
<th>Mandatory</th>
<th>Type</th>
<th>Desc</th>
<th>Default</th>
<th>Value Range</th>
</tr>
</thead><tbody>
<tr>
<td>contract_code</td>
<td>false</td>
<td>string</td>
<td>Case-Insenstive.Both uppercase and lowercase are supported..e.g. "BTC-USD"</td>
<td>if not filled in means all</td>
<td></td>
</tr>
</tbody></table>
<h4 id="note-4">Note</h4>
<ul>
<li>The interface data updated frequency is 50ms</li>
</ul>



<p><br>
<br>
<br>
<br>
<br></p>

      </div>
      <!-- <div class="dark-box">
          <div class="lang-selector">
                <a href="https://huobiapi.github.io/docs/coin_margined_swap/v1/en/#" data-language-name="shell" class="active">shell</a>
          </div>
      </div> -->
    </div>
</div>
</template>

<script>
export default {}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}

.highlight table td { padding: 5px; }
.highlight table pre { margin: 0; }
.highlight .gh {
  color: #999999;
}
.highlight .sr {
  color: #f6aa11;
}
.highlight .go {
  color: #888888;
}
.highlight .gp {
  color: #555555;
}
.highlight .gs {
}
.highlight .gu {
  color: #aaaaaa;
}
.highlight .nb {
  color: #f6aa11;
}
.highlight .cm {
  color: #75715e;
}
.highlight .cp {
  color: #75715e;
}
.highlight .c1 {
  color: #75715e;
}
.highlight .cs {
  color: #75715e;
}
.highlight .c, .highlight .cd {
  color: #75715e;
}
.highlight .err {
  color: #960050;
}
.highlight .gr {
  color: #960050;
}
.highlight .gt {
  color: #960050;
}
.highlight .gd {
  color: #49483e;
}
.highlight .gi {
  color: #49483e;
}
.highlight .ge {
  color: #49483e;
}
.highlight .kc {
  color: #66d9ef;
}
.highlight .kd {
  color: #66d9ef;
}
.highlight .kr {
  color: #66d9ef;
}
.highlight .no {
  color: #66d9ef;
}
.highlight .kt {
  color: #66d9ef;
}
.highlight .mf {
  color: #ae81ff;
}
.highlight .mh {
  color: #ae81ff;
}
.highlight .il {
  color: #ae81ff;
}
.highlight .mi {
  color: #ae81ff;
}
.highlight .mo {
  color: #ae81ff;
}
.highlight .m, .highlight .mb, .highlight .mx {
  color: #ae81ff;
}
.highlight .sc {
  color: #ae81ff;
}
.highlight .se {
  color: #ae81ff;
}
.highlight .ss {
  color: #ae81ff;
}
.highlight .sd {
  color: #e6db74;
}
.highlight .s2 {
  color: #e6db74;
}
.highlight .sb {
  color: #e6db74;
}
.highlight .sh {
  color: #e6db74;
}
.highlight .si {
  color: #e6db74;
}
.highlight .sx {
  color: #e6db74;
}
.highlight .s1 {
  color: #e6db74;
}
.highlight .s {
  color: #e6db74;
}
.highlight .na {
  color: #a6e22e;
}
.highlight .nc {
  color: #a6e22e;
}
.highlight .nd {
  color: #a6e22e;
}
.highlight .ne {
  color: #a6e22e;
}
.highlight .nf {
  color: #a6e22e;
}
.highlight .vc {
  color: #ffffff;
}
.highlight .nn {
  color: #ffffff;
}
.highlight .nl {
  color: #ffffff;
}
.highlight .ni {
  color: #ffffff;
}
.highlight .bp {
  color: #ffffff;
}
.highlight .vg {
  color: #ffffff;
}
.highlight .vi {
  color: #ffffff;
}
.highlight .nv {
  color: #ffffff;
}
.highlight .w {
  color: #ffffff;
}
.highlight {
  color: #ffffff;
}
.highlight .n, .highlight .py, .highlight .nx {
  color: #ffffff;
}
.highlight .ow {
  color: #f92672;
}
.highlight .nt {
  color: #f92672;
}
.highlight .k, .highlight .kv {
  color: #f92672;
}
.highlight .kn {
  color: #f92672;
}
.highlight .kp {
  color: #f92672;
}
.highlight .o {
  color: #f92672;
}
</style>
