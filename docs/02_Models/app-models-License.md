app\models\License
===============






* Class name: License
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $currencies

    public mixed $currencies = array('AUD', 'USD')





* Visibility: **public**
* This property is **static**.


### $contract_version

    public mixed $contract_version = array('V1' => 'V1', 'V2' => 'V2', 'V3' => 'V3', 'V4' => 'V4', 'V5' => 'V5', 'V6' => 'V6', 'V7' => 'V7', 'V8' => 'V8', 'V9' => 'V9')





* Visibility: **public**
* This property is **static**.


### $legal_entity

    public mixed $legal_entity = array('F45 Training Pty Ltd', 'F45 Training Canada', 'Functional 45 Training Limited', 'F45 Training Asia Private Ltd  - Singapore', 'F45 Training Incorporated', 'F45 U LLC')





* Visibility: **public**
* This property is **static**.


### $cpi_frequency

    public mixed $cpi_frequency = array('Yearly', 'Never')





* Visibility: **public**
* This property is **static**.


### $contract_type

    public mixed $contract_type = array('License', 'Franchise', 'College Agreement')





* Visibility: **public**
* This property is **static**.


### $hasOne

    public mixed $hasOne = array('Franchisees' => array('key' => array('franchise_id' => 'id')))





* Visibility: **public**


### $taxList

    public mixed $taxList = array('0' => '0', '1' => '.1')





* Visibility: **public**
* This property is **static**.


### $marketingFundContributionSetting

    public mixed $marketingFundContributionSetting = array('' => '', '0' => 'Fixed Percentage', '1' => 'Fixed Monthly Amount', '2' => 'Higher of Percentage or Monthly Amount', '3' => 'Lesser of Percentage or Monthly Amount')





* Visibility: **public**
* This property is **static**.


### $monthly_currencies

    public mixed $monthly_currencies = array('ALL' => 'Albania Lek - ALL', 'AFN' => 'Afghanistan Afghani - AFN', 'ARS' => 'Argentina Peso - ARS', 'AWG' => 'Aruba Guilder - AWG', 'AUD' => 'Australia Dollar - AUD', 'AZN' => 'Azerbaijan New Manat - AZN', 'BSD' => 'Bahamas Dollar - BSD', 'BBD' => 'Barbados Dollar - BBD', 'BDT' => 'Bangladeshi taka - BDT', 'BYR' => 'Belarus Ruble - BYR', 'BZD' => 'Belize Dollar - BZD', 'BMD' => 'Bermuda Dollar - BMD', 'BOB' => 'Bolivia Boliviano - BOB', 'BAM' => 'Bosnia and Herzegovina Convertible Marka - BAM', 'BWP' => 'Botswana Pula - BWP', 'BGN' => 'Bulgaria Lev - BGN', 'BRL' => 'Brazil Real - BRL', 'BND' => 'Brunei Darussalam Dollar - BND', 'KHR' => 'Cambodia Riel - KHR', 'CAD' => 'Canada Dollar - CAD', 'KYD' => 'Cayman Islands Dollar - KYD', 'CLP' => 'Chile Peso - CLP', 'CNY' => 'China Yuan Renminbi - CNY', 'COP' => 'Colombia Peso - COP', 'CRC' => 'Costa Rica Colon - CRC', 'HRK' => 'Croatia Kuna - HRK', 'CUP' => 'Cuba Peso - CUP', 'CZK' => 'Czech Republic Koruna - CZK', 'DKK' => 'Denmark Krone - DKK', 'DOP' => 'Dominican Republic Peso - DOP', 'XCD' => 'East Caribbean Dollar - XCD', 'EGP' => 'Egypt Pound - EGP', 'SVC' => 'El Salvador Colon - SVC', 'EEK' => 'Estonia Kroon - EEK', 'EUR' => 'Euro Member Countries - EUR', 'FKP' => 'Falkland Islands (Malvinas) Pound - FKP', 'FJD' => 'Fiji Dollar - FJD', 'GHC' => 'Ghana Cedis - GHC', 'GIP' => 'Gibraltar Pound - GIP', 'GTQ' => 'Guatemala Quetzal - GTQ', 'GGP' => 'Guernsey Pound - GGP', 'GYD' => 'Guyana Dollar - GYD', 'HNL' => 'Honduras Lempira - HNL', 'HKD' => 'Hong Kong Dollar - HKD', 'HUF' => 'Hungary Forint - HUF', 'ISK' => 'Iceland Krona - ISK', 'INR' => 'India Rupee - INR', 'IDR' => 'Indonesia Rupiah - IDR', 'IRR' => 'Iran Rial - IRR', 'IMP' => 'Isle of Man Pound - IMP', 'ILS' => 'Israel Shekel - ILS', 'JMD' => 'Jamaica Dollar - JMD', 'JPY' => 'Japan Yen - JPY', 'JEP' => 'Jersey Pound - JEP', 'KZT' => 'Kazakhstan Tenge - KZT', 'KPW' => 'Korea (North) Won - KPW', 'KRW' => 'Korea (South) Won - KRW', 'KGS' => 'Kyrgyzstan Som - KGS', 'LAK' => 'Laos Kip - LAK', 'LVL' => 'Latvia Lat - LVL', 'LBP' => 'Lebanon Pound - LBP', 'LRD' => 'Liberia Dollar - LRD', 'LTL' => 'Lithuania Litas - LTL', 'MKD' => 'Macedonia Denar - MKD', 'MYR' => 'Malaysia Ringgit - MYR', 'MUR' => 'Mauritius Rupee - MUR', 'MXN' => 'Mexico Peso - MXN', 'MNT' => 'Mongolia Tughrik - MNT', 'MZN' => 'Mozambique Metical - MZN', 'NAD' => 'Namibia Dollar - NAD', 'NPR' => 'Nepal Rupee - NPR', 'ANG' => 'Netherlands Antilles Guilder - ANG', 'NZD' => 'New Zealand Dollar - NZD', 'NIO' => 'Nicaragua Cordoba - NIO', 'NGN' => 'Nigeria Naira - NGN', 'NOK' => 'Norway Krone - NOK', 'OMR' => 'Oman Rial - OMR', 'PKR' => 'Pakistan Rupee - PKR', 'PAB' => 'Panama Balboa - PAB', 'PYG' => 'Paraguay Guarani - PYG', 'PEN' => 'Peru Nuevo Sol - PEN', 'PHP' => 'Philippines Peso - PHP', 'PLN' => 'Poland Zloty - PLN', 'QAR' => 'Qatar Riyal - QAR', 'RON' => 'Romania New Leu - RON', 'RUB' => 'Russia Ruble - RUB', 'SHP' => 'Saint Helena Pound - SHP', 'SAR' => 'Saudi Arabia Riyal - SAR', 'RSD' => 'Serbia Dinar - RSD', 'SCR' => 'Seychelles Rupee - SCR', 'SGD' => 'Singapore Dollar - SGD', 'SBD' => 'Solomon Islands Dollar - SBD', 'SOS' => 'Somalia Shilling - SOS', 'ZAR' => 'South Africa Rand - ZAR', 'LKR' => 'Sri Lanka Rupee - LKR', 'SEK' => 'Sweden Krona - SEK', 'CHF' => 'Switzerland Franc - CHF', 'SRD' => 'Suriname Dollar - SRD', 'SYP' => 'Syria Pound - SYP', 'TWD' => 'Taiwan New Dollar - TWD', 'THB' => 'Thailand Baht - THB', 'TTD' => 'Trinidad and Tobago Dollar - TTD', 'TRY' => 'Turkey Lira - TRY', 'TRL' => 'Turkey Lira - TRL', 'TVD' => 'Tuvalu Dollar - TVD', 'UAH' => 'Ukraine Hryvna - UAH', 'GBP' => 'United Kingdom Pound - GBP', 'UGX' => 'Uganda Shilling - UGX', 'USD' => 'United States Dollar - USD', 'UYU' => 'Uruguay Peso - UYU', 'UZS' => 'Uzbekistan Som - UZS', 'VEF' => 'Venezuela Bolivar - VEF', 'VND' => 'Viet Nam Dong - VND', 'YER' => 'Yemen Rial - YER', 'ZWD' => 'Zimbabwe Dollar - ZWD')





* Visibility: **public**
* This property is **static**.


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'franchise_id' => 'integer', 'key_person_name' => 'string', 'key_person_email' => 'string', 'key_person_mobile' => 'string', 'company_name' => 'string', 'trading_name' => 'string', 'abn' => 'string', 'law_firm' => 'string', 'lawyer_name' => 'string', 'lawyer_phone' => 'string', 'lawyer_email' => 'string', 'term1_years' => 'integer', 'term2_years' => 'integer', 'term3_years' => 'integer', 'term4_years' => 'integer', 'date_reserved' => 'date', 'deposit_taken' => 'boolean', 'deposit_amt' => 'float', 'currency' => 'string', 'establishment_fee' => 'float', 'establishment_fee_first_payment' => 'float', 'establishment_fee_second_payment' => 'float', 'establishment_fee_second_payment_due' => 'date', 'has_gst' => 'boolean', 'monthly_includes_gst' => 'boolean', 'date_contract_signed' => 'date', 'date_fee_started' => 'date', 'accounting_firm' => 'string', 'accountant_name' => 'string', 'accountant_phone' => 'string', 'accountant_email' => 'string', 'notes' => 'text', 'salesperson' => 'string', 'sales_agent' => 'string', 'currency_for_monthly' => 'string', 'all_fees_are_excluding_tax' => 'text', 'monthly_fee' => 'float', 'monthly_fee_date' => 'date', 'intranet_fee' => 'float', 'intranet_fee_start_date' => 'date', 'website_fee' => 'float', 'website_fee_start_date' => 'date', 'email_fee' => 'float', 'hr_tech_fee' => 'float', 'hr_tech_start_date' => 'date', 'includes_world_pack' => 'boolean', 'number_of_emails_currently' => 'integer', 'cpi_frequency' => 'string', 'cpi_or_fixed_percentage' => 'string', 'equipment_fee' => 'float', 'legal_entity' => 'string', 'contract_type' => 'string', 'contract_version' => 'string', 'total_upfront_fee_paid' => 'float', 'net_establishment_fee' => 'float', 'date_first_payment_received' => 'date', 'did_they_get_the_accountant_advise' => 'string', 'did_you_get_legal_advise' => 'string', 'did_you_get_business_advise' => 'string', 'key_person_name_2' => 'string', 'key_person_email_2' => 'string', 'key_person_mobile_2' => 'string', 'franchisee_renewal_notice_max_months' => 'integer', 'franchisee_renewal_notice_min_months' => 'integer', 'mango_map_exact_territory_name' => 'string', 'map' => 'string', 'timestamp' => 'timestamp', 'current_term' => 'string', 'equipment_schedule_pdf' => 'text', 'has_renewal_fee' => 'string', 'lionheart_platform_fee' => 'float', 'email_fee_start_date' => 'date', 'invoice_sent' => 'boolean', 'agreement_changes' => 'string', 'agreement_addendum' => 'string', 'email_waived' => 'boolean', 'intranet_waived' => 'boolean', 'website_waived' => 'boolean', 'renewal_fee_amount' => 'text', 'agreement' => 'string', 'address' => 'text', 'key_persons' => 'text', 'guarantors' => 'text', 'covenantors' => 'text', 'business_advisor' => 'string', 'business_advisor_name' => 'string', 'business_advisor_phone' => 'string', 'business_advisor_email' => 'string', 'contract_has_been_renewed' => 'string', 'contract_renewed_date' => 'date', 'directors' => 'text', 'fee_refundable' => 'string', 'fee_has_been_refunded' => 'string', 'fee_refunded_date' => 'date', 'renewal_fee_due_date' => 'date', 'renewal_fee_paid_date' => 'date', 'equipment_payments' => 'text', 'establishment_payments' => 'text', 'contract_termination_date' => 'date', 'agreement_financial_terms' => 'text', 'disclosure_document_receipt' => 'text', 'is_confirmed' => 'boolean', 'confirmed_by' => 'string', 'is_audited' => 'boolean', 'monthly_fee_or_franaggrement' => 'boolean', 'audited_by' => 'string', 'history' => 'text')





* Visibility: **protected**


### $validates

    public mixed $validates = array('franchisee_id' => array(array('notEmpty', 'message' => 'You must include a Franchised ID.'), array('isFranchiseeUnique', 'message' => 'Franchisee is already used. One license per franchisee')))





* Visibility: **public**


Methods
-------


### financialReports

    mixed app\models\License::financialReports($country, $start_date, $end_date, $legal_entity)

Financial Reports



* Visibility: **public**
* This method is **static**.


#### Arguments
* $country **mixed**
* $start_date **mixed**
* $end_date **mixed**
* $legal_entity **mixed**



### financialReportsAll

    mixed app\models\License::financialReportsAll($start_date, $end_date)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $start_date **mixed**
* $end_date **mixed**



### getInvoiceSentByStat

    \app\models\[type] app\models\License::getInvoiceSentByStat(\app\models\[type] $status)

Get List of studios added starting from October 19, 2016
with invoices sent not ticked on this page



* Visibility: **public**
* This method is **static**.


#### Arguments
* $status **app\models\[type]** - &lt;p&gt;[description]&lt;/p&gt;



### get_contract_expiring

    mixed app\models\License::get_contract_expiring($months)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $months **mixed**


