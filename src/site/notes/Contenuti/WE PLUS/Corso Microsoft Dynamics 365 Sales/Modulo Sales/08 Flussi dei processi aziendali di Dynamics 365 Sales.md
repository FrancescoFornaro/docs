---
{"dg-publish":true,"permalink":"/contenuti/we-plus/corso-microsoft-dynamics-365-sales/modulo-sales/08-flussi-dei-processi-aziendali-di-dynamics-365-sales/"}
---


Molte organizzazioni dispongono di processi che utilizzano durante il ciclo di vita delle vendite per garantire di avere la migliore opportunità di concludere una trattativa. Ad esempio, durante il tentativo di qualificare un lead, un'organizzazione potrebbe chiedere ai propri rappresentanti di vendita di eseguire attività che aiutano a identificare se si tratta di un'opportunità praticabile. I rappresentanti di vendita identificano il modo in cui un'azienda acquista gli articoli, acquisiscono i tempi di acquisto e acquisiscono altre informazioni rilevanti. Una volta qualificato, il lead potrebbe identificare altri elementi come le entrate o la necessità di eseguire una verifica del credito.

I flussi di processi aziendali (BPF) in Dynamics 365 forniscono una guida su come portare a termine il lavoro. Forniscono un'esperienza utente semplificata che guida le persone attraverso processi specifici definiti dalla loro organizzazione. Ad esempio, Contoso Coffee utilizza i flussi dei processi aziendali per guidare i venditori attraverso il processo di qualificazione di un lead, gestione dell'opportunità, preparazione del preventivo e generazione di un ordine.

Un flusso di processo aziendale è costituito dagli elementi principali di fasi e passaggi. Dal punto di vista delle vendite, una fase BPF potrebbe rappresentare una fase del processo di vendita, ad esempio la qualificazione di un cliente o la proposta di una soluzione. La scena, a sua volta, contiene passaggi. Questi passaggi sono campi che possono essere compilati man mano che vengono completati, ad esempio selezionando una casella dopo aver identificato il decisore.

Per impostazione predefinita, Dynamics 365 Sales viene fornito con due flussi di processi aziendali integrati destinati alle vendite.

* **Processo di vendita da lead a opportunità**: processo di vendita composto da quattro fasi **Qualifica** > **Sviluppa** > **Proponi** > **Chiudi** che inizia con un record lead e si estende fino alla chiusura di un'opportunità.

* **Processo di vendita dell'opportunità**: come il processo Lead to Opportunity, si compone delle stesse quattro fasi, tranne che inizia quando viene creata un'opportunità.

Nell'immagine è possibile vedere un esempio del processo Lead to Opportunity applicato a un lead appena creato per Contoso Coffee.

![2023-11-30 Microsoft Dynamics Sales 13.png](/img/user/Allegati/2023-11-30%20Microsoft%20Dynamics%20Sales%2013.png)

Durante la fase di qualificazione, ti vengono presentati i passaggi per acquisire elementi come il processo di acquisto, il budget stimato, il periodo di tempo di acquisto e altro ancora. Una volta pronto, puoi facilmente avanzare alla fase di sviluppo, prima di passare alle fasi di proposta e chiusura. Ciò garantisce che tutto il personale di vendita segua gli stessi processi ripetibili per massimizzare le possibilità di concludere affari e garantire che nulla venga perso.

# Demo click-through: flusso dei processi aziendali

In questa dimostrazione a portata di clic, verrai guidato attraverso un tipico processo di gestione dei lead. Ciò include la creazione di un nuovo lead nell'applicazione e l'utilizzo della funzionalità Dynamics 365 Sales per spostarlo attraverso il processo di qualificazione.

(video)

Come hai visto, Dynamics 365 Sales semplifica l'acquisizione e la qualificazione dei lead da parte dei singoli utenti. I lead possono essere facilmente creati in diversi modi per adattarsi a diversi modelli di vendita. Una volta creati, i flussi dei processi aziendali aiutano i venditori a garantire che stiano acquisendo le informazioni necessarie e seguendo i passaggi necessari per garantire di qualificare solo i lead che soddisfano i criteri di qualificazione dei lead della loro organizzazione.

**Mettendo tutto insieme**

Ora che abbiamo esaminato queste funzionalità singolarmente, esaminiamo come viene utilizzata la combinazione di tutte le funzionalità di cui abbiamo discusso per spostare il lead qualificato di John in un'opportunità.

![2023-11-30 Microsoft Dynamics Sales 14.png](/img/user/Allegati/2023-11-30%20Microsoft%20Dynamics%20Sales%2014.png)

* **Qualificazione**: John ha qualificato il lead utilizzando il processo di qualificazione del lead descritto in precedenza.

* **Sviluppo**: il record avanza automaticamente alla fase di sviluppo quando il lead viene convertito in un'opportunità.
* John completa tutte le informazioni aggiuntive necessarie per l'opportunità, ad esempio la data di chiusura prevista, le esigenze del cliente e le informazioni sul budget.

	* Vengono aggiunti gli stakeholder che rappresentano i membri del team di progetto, i membri del comitato consultivo, i consulenti legali, ecc.

	* Vengono aggiunti i concorrenti contro cui stiamo gareggiando per sfruttare l'opportunità.

* I prodotti e le informazioni sui prezzi sono definiti.

	* L'opportunità è impostata per utilizzare i prezzi calcolati dal sistema e il listino prezzi al dettaglio è definito.

	* Ogni voce viene inclusa e le informazioni sui prezzi vengono definite.

* È previsto un incontro con il cliente tra una settimana a partire da oggi.

	* L'assistente alle relazioni ricorda l'appuntamento al responsabile commerciale.

	* Durante l'incontro il cliente chiede una proposta formale sulla soluzione.

* John avanza l'opportunità per la fase di proposta.

* **Proposta**: un preventivo formale viene generato e consegnato al cliente.

	* Vengono definite le risorse di vendita interne necessarie per l'opportunità.
		* Vengono aggiunti i membri del team di vendita.
			* Facoltativamente, è possibile utilizzare i team di accesso per fornire l'accesso ai record ai membri definiti.

* All'opportunità viene aggiunto un preventivo che include tutti i prodotti definiti nell'opportunità.

* È previsto un incontro con il cliente per presentargli formalmente il preventivo.

* Il team prepara una presentazione finale allegata all'opportunità.
	* Facoltativamente, è possibile utilizzare l'integrazione con SharePoint o OneDrive for Business per archiviare i documenti correlati.

* Il preventivo viene attivato e presentato al cliente durante il meeting.

* Gli appunti sull'incontro vengono aggiornati.

* Il cliente accetta il preventivo.

* John avanza l'opportunità alla fase di chiusura.

* **Chiusura**: le attività necessarie per chiudere l'opportunità sono state completate.

* La proposta finale viene consegnata e firmata dal cliente.

* Il preventivo viene convertito in un ordine e chiuso.

* L'opportunità è chiusa.

Le opportunità possono essere chiuse in diversi modi. Possono essere chiusi automaticamente quando viene chiuso un preventivo associato o quando viene creato un ordine da un preventivo. Lo esamineremo un po' più tardi. L'altro modo è chiudere l'opportunità manualmente.

Rivedi bene → [Describe Dynamics 365 Sales business process flows - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/explore-dynamics-365-sales/8-describe-dynamics-365-sales-business-process-flows)
***

Vai alla lezione successiva → [[Contenuti/WE PLUS/Corso Microsoft Dynamics 365 Sales/Modulo Sales/09 Acceleratore delle vendite\|09 Acceleratore delle vendite]]

