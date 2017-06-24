/=Demo Deal Points

//=Participants:

Company.=[G/U/id/acme_incorporated.md]

Seed.1.=[G/U/id/andrea_ang.md]

Seed.2.=[G/U/id/abigail_altima.md]

Seed.3.=[G/U/id/alison_andrews.md]

KeyHolder.1.=[G/U/id/barbara_oreilly.md]

KeyHolder.2.=[G/U/id/geraldine_graber.md]

KeyHolder.3.=[G/U/id/quentin_quade.md]

Director.1.=[G/U/id/barbara_oreilly.md]

Director.2.=[G/U/id/geraldine_graber.md]

Director.3.=[G/U/id/solomon_shirley.md]

//=Dates:

EffectiveDate.YMD=2017-06-21

ClosingDate.YMD=2017-07-06

Law.=[G/U/at/US/CA/San_Francisco/San_Francisco/Geo]

StockPlan.Title,Date.cl=Acme Employee Stock Plan

//=Board:

TotalBoardMemberCount.#=7

CommonBoardMemberCount.#=3

MutualConsentBoardMemberCount.#=2

SeedBoardMemberCount.#=2

//=Valuations:

Seed.PricePerShare.$=$10.00

Convert.Share.Quantity.#=10,000

LeadInvestor.By.Sec={Seed.1.US.Contract.By.Sec}

Convert.Share.Quantity.#=0

Purchaser.All.cl={Seed.1.Name.Full}, {Seed.2.Name.Full} and {Seed.3.Name.Full}

PremoneyValuation.$=$7,000,000

OptionPool.%=10%

CommonBoardMember.IDs.cl={KeyHolder.1.Name.Full}, {KeyHolder.2.Name.Full} and {KeyHolder.3.Name.Full}

SeedBoardMember.IDs.cl={Seed.1.Name.Full} and {Seed.2.Name.Full}

MutualConsentBoardMember.IDs.cl={Seed.3.Name.Full} and {Director.3.Name.Full}

MajorPurchaserDollarThreshold.$=$200,000

Seed.Round.Total.$=$400,000

UnallocatedPost-MoneyOptionPoolPercent.%=20%

PurchaserCounselReimbursementAmount.$=$20,000

KeyHolderVesting.Begin.YMD=2017-06-30

CommonShares IssuedAndOutstandingPre-Money.#=1,000,000

TotalPost-MoneySharesReservedForOptionPool.$=1,000,000

NumberOfIssuedAndOutstandingOptions.#=1,000,000

UnallocatedPostMoneyOptionPoolShares.#=1,000,000

Seed.1.Share.Quantity.#=20,000

Seed.1.Price.Debt.$=$0

Seed.1.Price.Cash.$=$200,000

Seed.1.Price.$=$200,000

Seed.1.Questionnaire.IndividualQualifies.ByIncome.?=<font color="magenta">YES</font>

Seed.1.Questionnaire.By.Sec={Seed.1.US.Contract.By.Sec}

Seed.2.Share.Quantity.#=10,000

Seed.2.Price.Debt.$=$50,000

Seed.2.Price.Cash.$=$50,000

Seed.2.Price.$=$100,000

Seed.3.Share.Quantity.#=10,000

Seed.3.Price.Debt.$=$0

Seed.3.Price.Cash.$=$100,000

Seed.3.Price.$=$100,000

KeyHolder.1.Share.Quantity.#=500,000

KeyHolder.2.Share.Quantity.#=200,000

KeyHolder.3.Share.Quantity.#=100,000

Seed.Authorized.Quantity.#=1,000,000

Seed.Quantity.#=50,000

Seed.Share.Price.$=$10.00

Common.ReservedForSeedConverstion.#=50,000

Share.Authorized.Quantity.#=3,000,000

Seed.Directors.Quantity.#=2

Share.Authorized.Quantity.#=5,000,000

Common.Authorized.Quantity.#=3,000,000

Common.Par.$=$0.10

Preferred.Authorized.Quantity.#=2,000,000

Preferred.Par.$=$0.10

Company.OriginalIncorporationDate.YMD=2016-02-02

Company.Original.Name.Full={Company.Name.Full}

KeyHolder.By.Sec={KeyHolder.1.US.Contract.By.Sec}<br>{KeyHolder.2.US.Contract.By.Sec}<br>{KeyHolder.3.US.Contract.By.Sec}

Seed.By.Sec={Seed.1.US.Contract.By.Sec}<br>{Seed.2.US.Contract.By.Sec}<br>{Seed.3.US.Contract.By.Sec}

Director.By.Sec={Director.1.US.Contract.By.Sec}<br>{Director.2.US.Contract.By.Sec}<br>{Director.3.US.Contract.By.Sec}

BoardMinutes.By.Sec={KeyHolder.2.US.Contract.By.Sec}

CertificateOfIncorporation.By.Sec={KeyHolder.2.US.Contract.By.Sec}

StockholderConsent.By.Sec={KeyHolder.1.US.Contract.By.Sec}<br>{KeyHolder.2.US.Contract.By.Sec}<br>{KeyHolder.3.US.Contract.By.Sec}

Company.Handle=Company

Sign.YMD=________________________  

xSignature=________________________

Seed.1.Handle=Ang

Seed.2.Handle=Altima

Seed.3.Handle=Andrews

KeyHolder.1.Handle=O'Reilly

KeyHolder.2.Handle=Graber

KeyHolder.3.Handle=Quade

Director.1.Handle=O'Reilly

Director.2.Handle=Graber

Director.3.Handle=Shirley