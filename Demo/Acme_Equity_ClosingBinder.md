//=First the deal specifications:
 
=[G/SeriesSeed-Cooley-CmA/Demo/Acme_Equity_DealPoints.md]

//=Then the set of forms:

PurchaseAgreement.=[G/SeriesSeed-Cooley-CmA/equity/Preferred_Stock_Investment_Agreement/Form/0.md]

BoardConsent.=[G/SeriesSeed-Cooley-CmA/equity/Board_Consent/0.md]

Seed.1.Questionnaire.=[G/SeriesSeed-Cooley-CmA/equity/Investor_Questionnaire/0.md]

CertificateOfIncorporation.=[G/SeriesSeed-Cooley-CmA/equity/Restated_Certificate_of_Incorporation/0.md]

//=Then select what document or documents (or Section of a document) you want to see:

/Model.Root={PurchaseAgreement.Sec}  

/Model.Root={BoardConsent.Sec}
  
/Model.Root={Seed.1.Questionnaire.Sec}

Model.Root={CertificateOfIncorporation.Sec}