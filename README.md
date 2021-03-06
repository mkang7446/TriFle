
<p align="center">
<img display="center" src="/src/Resouces/Logo%20for%20Readme.png"></img>
<p>

### Project Description 
> My project, TriFle is a real time stock search app that lets a user search stock price, stock market news and all listed companies' information. Also, it provides top 100 cryptocurrency list. 

## URL
> https://loving-knuth-39ffe9.netlify.app

## Demo
> ![Demo](https://user-images.githubusercontent.com/92760530/157303843-4f4b1078-087e-4ca2-a0eb-d3669ad7911b.gif)

## Wire Frames
![P1 - Wire Frame](https://user-images.githubusercontent.com/92760530/157293971-5766d8a5-bd0e-4b3a-b399-41fca1053b8f.png)

## APIs used
* https://www.alphavantage.co/
* https://finnhub.io/
* https://www.coingecko.com/

## Technologies Used
* HTML
* CSS
* React
* Chart.js
* NPM

## Component Hierarchy
![P1 - Component Hierachy](https://user-images.githubusercontent.com/92760530/157293978-05d0ce96-03ee-4b8a-8d5c-3b1404265b30.png)


### Finnhub API
> #1 Simple Quote
```
{
c: 159.3,
d: -3.87,
dp: -2.3718,
h: 165.02,
l: 159.04,
o: 163.36,
pc: 163.17,
t: 1646686803
}
```
> #2 6 months candlestick data
```
{
c: [
155.23,
155.1,
155.26,
155.15,
155.18,
155.27,
155.15,
155.1,
155.18,
155.19,
155.41,
155.51,
155.61,
155.565,
155.71,
155.66,
155.69,
155.85,
155.855,
155.72,
155.65,
155.49,
155.44,
155.688
]
}
```

### Alpha Vantage API
```
{
    Symbol: "IBM",
    AssetType: "Common Stock",
    Name: "International Business Machines Corporation",
    Description: "International Business Machines Corporation (IBM) is an American multinational technology company headquartered in Armonk, New York, with operations in over 170 countries. The company began in 1911, founded in Endicott, New York, as the Computing-Tabulating-Recording Company (CTR) and was renamed International Business Machines in 1924. IBM is incorporated in New York. IBM produces and sells computer hardware, middleware and software, and provides hosting and consulting services in areas ranging from mainframe computers to nanotechnology. IBM is also a major research organization, holding the record for most annual U.S. patents generated by a business (as of 2020) for 28 consecutive years. Inventions by IBM include the automated teller machine (ATM), the floppy disk, the hard disk drive, the magnetic stripe card, the relational database, the SQL programming language, the UPC barcode, and dynamic random-access memory (DRAM). The IBM mainframe, exemplified by the System/360, was the dominant computing platform during the 1960s and 1970s.",
    CIK: "51143",
    Exchange: "NYSE",
    Currency: "USD",
    Country: "USA",
    Sector: "TECHNOLOGY",
    Industry: "COMPUTER & OFFICE EQUIPMENT",
    Address: "1 NEW ORCHARD ROAD, ARMONK, NY, US",
    FiscalYearEnd: "December",
    LatestQuarter: "2021-12-31",
    MarketCapitalization: "111676300000",
    EBITDA: "12189000000",
    PERatio: "28.76",
    PEGRatio: "1.184",
    BookValue: "21.05",
    DividendPerShare: "6.56",
    DividendYield: "0.0528",
    EPS: "6.34",
    RevenuePerShareTTM: "64.01",
    ProfitMargin: "0.1",
    OperatingMarginTTM: "0.101",
    ReturnOnAssetsTTM: "0.0251",
    ReturnOnEquityTTM: "23.86",
    RevenueTTM: "57351000000",
    GrossProfitTTM: "31486000000",
    DilutedEPSTTM: "6.35",
    QuarterlyEarningsGrowthYOY: "0.696",
    QuarterlyRevenueGrowthYOY: "0.692",
    AnalystTargetPrice: "143.47",
    TrailingPE: "19.3",
    ForwardPE: "12.17",
    PriceToSalesRatioTTM: "1.915",
    PriceToBookRatio: "5.91",
    EVToRevenue: "2.782",
    EVToEBITDA: "12.86",
    Beta: "1.089",
    52WeekHigh: "140.73",
    52WeekLow: "108.14",
    50DayMovingAverage: "131.84",
    200DayMovingAverage: "131.81",
    SharesOutstanding: "896320000",
    DividendDate: "2022-03-10",
    ExDividendDate: "2022-02-10"
}
```

### CoinGecko API
```
[
{
id: "bitcoin",
symbol: "btc",
name: "Bitcoin",
image: "https://assets.coingecko.com/coins/images/1/large/bitcoin.png?1547033579",
current_price: 39094,
market_cap: 735415412048,
market_cap_rank: 1,
fully_diluted_valuation: 813780840693,
total_volume: 25795543552,
high_24h: 39101,
low_24h: 37275,
price_change_24h: 375.9,
price_change_percentage_24h: 0.97085,
market_cap_change_24h: -167928909.08007812,
market_cap_change_percentage_24h: -0.02283,
circulating_supply: 18977743,
total_supply: 21000000,
max_supply: 21000000,
ath: 69045,
ath_change_percentage: -43.88102,
ath_date: "2021-11-10T14:24:11.849Z",
atl: 67.81,
atl_change_percentage: 57041.71035,
atl_date: "2013-07-06T00:00:00.000Z",
roi: null,
last_updated: "2022-03-08T17:38:25.918Z"
},
]
```

## User Stories
> 
* As a user, I want to see a clearly seperated header and main sections with initial top 5 companies' stock information.
* As a user, I want to search for a company by symbol or name and click a link to view stock details such as description, price graph and other information.
* As a user, I want to go to About and News pages to see contents by clicking buttons on the navigation bar.
* As a user, I want to be able to use this application on a mobile friendly version.

## MVP Goals
>
* Create all required component files and organize them in each folder.
* Make functions in each component and check if imported & exported successfully.
* Render useState & useEffect and fetch.
* Build Header section with search input bar and links into About & News.
* Make top 5 companies stock info for default when the application is loaded at first time.
* Build Routes and make a link to get into stock information with details.
* Add error handling statements.

## MVP Stretch Goals
>
* Find a graph library and apply it in each detail page.
* Create my own logo and text design.
* Apply a small version of the graph into my favorite list.
