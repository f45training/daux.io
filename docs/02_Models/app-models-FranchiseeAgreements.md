app\models\FranchiseeAgreements
===============






* Class name: FranchiseeAgreements
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $_status

    public mixed $_status = array('draft' => 'draft', 'active' => 'active')





* Visibility: **public**
* This property is **static**.


### $EquipmentDelivery

    public mixed $EquipmentDelivery = array('Select equipment delivery', 'Included in equipment fee', 'Excluded in equipment fee')





* Visibility: **public**
* This property is **static**.


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'title' => 'string', 'description' => 'string', 'from_date' => 'date', 'to_date' => 'date', 'status' => 'string', 'franchisee_id' => 'integer', 'company_name' => 'string', 'trading_name' => 'string', 'abn' => 'string', 'address' => 'text', 'is_confirmed' => 'boolean', 'confirmed_by' => 'string', 'is_audited' => 'boolean', 'audited_by' => 'string', 'term1_years' => 'string', 'term2_years' => 'string', 'term3_years' => 'string', 'term4_years' => 'string', 'terms_contact_date' => 'text', 'current_term' => 'string', 'agreement_changes' => 'text', 'mango_map_exact_territory_name' => 'string', 'map' => 'string', 'agreement' => 'string', 'agreement_addendum' => 'string', 'equipment_schedule_pdf' => 'string', 'agreement_financial_terms' => 'string', 'bank_details_form' => 'string', 'date_reserved' => 'date', 'date_contract_signed' => 'date', 'contract_termination_date' => 'date', 'monthly_fee_date' => 'date', 'intranet_fee_start_date' => 'date', 'website_fee_start_date' => 'date', 'hr_tech_start_date' => 'date', 'hr_tech_start_date_default' => 'string', 'email_fee_start_date' => 'date', 'franchisee_renewal_notice_min_months' => 'string', 'franchisee_renewal_notice_max_months' => 'string', 'contract_has_been_renewed' => 'string', 'contract_renewed_date' => 'date', 'renewal_fee_due_date' => 'date', 'renewal_fee_paid_date' => 'date', 'establishment_payments' => 'text', 'currency' => 'string', 'equipment_delivery' => 'string', 'equipment_fee' => 'string', 'includes_world_pack' => 'boolean', 'establishment_fee' => 'string', 'establishment_fee_first_payment' => 'string', 'date_first_payment_received' => 'date', 'establishment_fee_second_payment' => 'string', 'establishment_fee_second_payment_due' => 'date', 'deposit_amt' => 'string', 'fee_has_been_refunded' => 'string', 'fee_refunded_date' => 'date', 'all_fees_are_excluding_tax' => 'boolean', 'invoice_sent' => 'boolean', 'has_gst' => 'boolean', 'deposit_taken' => 'boolean', 'has_renewal_fee' => 'string', 'renewal_fee_amount' => 'string', 'cpi_or_fixed_percentage' => 'string', 'cpi_frequency' => 'string', 'currency_for_monthly' => 'string', 'monthly_includes_gst' => 'boolean', 'email_waived' => 'string', 'intranet_waived' => 'string', 'website_waived' => 'string', 'monthly_fee' => 'string', 'intranet_fee' => 'string', 'website' => 'string', 'lionheart_platform_fee' => 'string', 'email_fee' => 'string', 'did_you_get_legal_advise' => 'string', 'law_firm' => 'string', 'lawyer_name' => 'string', 'lawyer_phone' => 'string', 'lawyer_email' => 'string', 'did_they_get_the_accountant_advise' => 'string', 'accounting_firm' => 'string', 'accountant_name' => 'string', 'accountant_phone' => 'string', 'accountant_email' => 'string', 'did_you_get_business_advise' => 'string', 'business_advisor' => 'string', 'business_advisor_name' => 'string', 'business_advisor_phone' => 'string', 'business_advisor_email' => 'string', 'legal_entity' => 'string', 'contract_type' => 'string', 'contract_version' => 'string', 'salesperson' => 'string', 'sales_agent' => 'string', 'notes' => 'string', 'website_fee' => 'string', 'is_subscribed' => 'boolean', 'timestamp' => 'timestamp', 'is_deleted' => 'boolean', 'disclosure_document_receipt' => 'text', 'agreement_other_documents' => 'text', 'province' => 'string', 'gst_hst' => 'string', 'vat_number' => 'string', 'equipment_payments' => 'text', 'state' => 'string', 'effective_date' => 'date', 'second_studio_fee' => 'float', 'second_studio_license_fees' => 'float', 'deferral' => 'boolean', 'deferral_val' => 'text', 'specific_addendum' => 'boolean', 'state_specific_addendum' => 'text', 'group_name' => 'string', 'monthly_fee_notes' => 'text', 'is_financed' => 'boolean', 'is_show_extension_deferral_fees_request' => 'boolean', 'finance_provider' => 'text', 'finance_amount' => 'string', 'establishment_fee_due_date_default' => 'string', 'establishment_fee_due_date' => 'date', 'monthly_fee_start_date_default' => 'string', 'equipment_fee_due_date_default' => 'string', 'equipment_fee_due_date' => 'date', 'marketing_currency' => 'string', 'grand_opening' => 'string', 'fund_setting' => 'string', 'fund_percentage_gross_revenue' => 'string', 'fund_monthly_amount' => 'string', 'paid_franchisor' => 'string', 'local_advert_setting' => 'string', 'local_advert_gross_revenue' => 'string', 'local_advert_monthly_amount' => 'string', 'display_gross_revenue' => 'string', 'assessment_gross_revenue' => 'string', 'franchisors_cost' => 'string', 'transfer_fee' => 'string', 'is_blacklisted' => 'boolean', 'reason' => 'text', 'is_blacklisted_id' => 'integer', 'is_creche_request' => 'boolean')





* Visibility: **protected**


### $provinces

    public mixed $provinces = array('AB' => '5% GST', 'BC' => '5% GST', 'MB' => '5% GST', 'NB' => '15% HST', 'NL' => '15% HST', 'NS' => '15% HST', 'NT' => '5% GST', 'NU' => '5% GST', 'ON' => '13% HST', 'PE' => '15% HST', 'QC' => '5% GST', 'SK' => '5% GST', 'YT' => '5% GST')





* Visibility: **public**
* This property is **static**.


### $europe

    public mixed $europe = array('Albania' => 'Albania', 'Andorra' => 'Andorra', 'Armenia' => 'Armenia', 'Austria' => 'Austria', 'Azerbaijan' => 'Azerbaijan', 'Belarus' => 'Belarus', 'Belgium' => 'Belgium', 'Bosnia and Herzegovina' => 'Bosnia and Herzegovina', 'Bulgaria' => 'Bulgaria', 'Croatia' => 'Croatia', 'Cyprus' => 'Cyprus', 'Czech Republic' => 'Czech Republic', 'Denmark' => 'Denmark', 'Estonia' => 'Estonia', 'Finland' => 'Finland', 'France' => 'France', 'Georgia' => 'Georgia', 'Germany' => 'Germany', 'Greece' => 'Greece', 'Hungary' => 'Hungary', 'Iceland' => 'Iceland', 'Ireland' => 'Ireland', 'Italy' => 'Italy', 'Kazakhstan' => 'Kazakhstan', 'Kosovo' => 'Kosovo', 'Latvia' => 'Latvia', 'Liechtenstein' => 'Liechtenstein', 'Lithuania' => 'Lithuania', 'Luxembourg' => 'Luxembourg', 'Macedonia' => 'Macedonia', 'Malta' => 'Malta', 'Moldova' => 'Moldova', 'Monaco' => 'Monaco', 'Montenegro' => 'Montenegro', 'Netherlands' => 'Netherlands', 'Norway' => 'Norway', 'Poland' => 'Poland', 'Portugal' => 'Portugal', 'Romania' => 'Romania', 'Russia' => 'Russia', 'San Marino' => 'San Marino', 'Serbia' => 'Serbia', 'Slovakia' => 'Slovakia', 'Slovenia' => 'Slovenia', 'Spain' => 'Spain', 'Sweden' => 'Sweden', 'Switzerland' => 'Switzerland', 'Turkey' => 'Turkey', 'Ukraine' => 'Ukraine', 'United Kingdom' => 'United Kingdom', 'Vatican City' => 'Vatican City')





* Visibility: **public**
* This property is **static**.


### $currency

    public mixed $currency = array("BD" => "BDT", "BE" => "EUR", "BF" => "XOF", "BG" => "BGN", "BA" => "BAM", "BB" => "BBD", "WF" => "XPF", "BL" => "EUR", "BM" => "BMD", "BN" => "BND", "BO" => "BOB", "BH" => "BHD", "BI" => "BIF", "BJ" => "XOF", "BT" => "BTN", "JM" => "JMD", "BV" => "NOK", "BW" => "BWP", "WS" => "WST", "BQ" => "USD", "BR" => "BRL", "BS" => "BSD", "JE" => "GBP", "BY" => "BYR", "BZ" => "BZD", "RU" => "RUB", "RW" => "RWF", "RS" => "RSD", "TL" => "USD", "RE" => "EUR", "TM" => "TMT", "TJ" => "TJS", "RO" => "RON", "TK" => "NZD", "GW" => "XOF", "GU" => "USD", "GT" => "GTQ", "GS" => "GBP", "GR" => "EUR", "GQ" => "XAF", "GP" => "EUR", "JP" => "JPY", "GY" => "GYD", "GG" => "GBP", "GF" => "EUR", "GE" => "GEL", "GD" => "XCD", "GB" => "GBP", "GA" => "XAF", "SV" => "USD", "GN" => "GNF", "GM" => "GMD", "GL" => "DKK", "GI" => "GIP", "GH" => "GHS", "OM" => "OMR", "TN" => "TND", "JO" => "JOD", "HR" => "HRK", "HT" => "HTG", "HU" => "HUF", "HK" => "HKD", "HN" => "HNL", "HM" => "AUD", "VE" => "VEF", "PR" => "USD", "PS" => "ILS", "PW" => "USD", "PT" => "EUR", "SJ" => "NOK", "PY" => "PYG", "IQ" => "IQD", "PA" => "PAB", "PF" => "XPF", "PG" => "PGK", "PE" => "PEN", "PK" => "PKR", "PH" => "PHP", "PN" => "NZD", "PL" => "PLN", "PM" => "EUR", "ZM" => "ZMK", "EH" => "MAD", "EE" => "EUR", "EG" => "EGP", "ZA" => "ZAR", "EC" => "USD", "IT" => "EUR", "VN" => "VND", "SB" => "SBD", "ET" => "ETB", "SO" => "SOS", "ZW" => "ZWL", "SA" => "SAR", "ES" => "EUR", "ER" => "ERN", "ME" => "EUR", "MD" => "MDL", "MG" => "MGA", "MF" => "EUR", "MA" => "MAD", "MC" => "EUR", "UZ" => "UZS", "MM" => "MMK", "ML" => "XOF", "MO" => "MOP", "MN" => "MNT", "MH" => "USD", "MK" => "MKD", "MU" => "MUR", "MT" => "EUR", "MW" => "MWK", "MV" => "MVR", "MQ" => "EUR", "MP" => "USD", "MS" => "XCD", "MR" => "MRO", "IM" => "GBP", "UG" => "UGX", "TZ" => "TZS", "MY" => "MYR", "MX" => "MXN", "IL" => "ILS", "FR" => "EUR", "IO" => "USD", "SH" => "SHP", "FI" => "EUR", "FJ" => "FJD", "FK" => "FKP", "FM" => "USD", "FO" => "DKK", "NI" => "NIO", "NL" => "EUR", "NO" => "NOK", "NA" => "NAD", "VU" => "VUV", "NC" => "XPF", "NE" => "XOF", "NF" => "AUD", "NG" => "NGN", "NZ" => "NZD", "NP" => "NPR", "NR" => "AUD", "NU" => "NZD", "CK" => "NZD", "XK" => "EUR", "CI" => "XOF", "CH" => "CHF", "CO" => "COP", "CN" => "CNY", "CM" => "XAF", "CL" => "CLP", "CC" => "AUD", "CA" => "CAD", "CG" => "XAF", "CF" => "XAF", "CD" => "CDF", "CZ" => "CZK", "CY" => "EUR", "CX" => "AUD", "CR" => "CRC", "CW" => "ANG", "CV" => "CVE", "CU" => "CUP", "SZ" => "SZL", "SY" => "SYP", "SX" => "ANG", "KG" => "KGS", "KE" => "KES", "SS" => "SSP", "SR" => "SRD", "KI" => "AUD", "KH" => "KHR", "KN" => "XCD", "KM" => "KMF", "ST" => "STD", "SK" => "EUR", "KR" => "KRW", "SI" => "EUR", "KP" => "KPW", "KW" => "KWD", "SN" => "XOF", "SM" => "EUR", "SL" => "SLL", "SC" => "SCR", "KZ" => "KZT", "KY" => "KYD", "SG" => "SGD", "SE" => "SEK", "SD" => "SDG", "DO" => "DOP", "DM" => "XCD", "DJ" => "DJF", "DK" => "DKK", "VG" => "USD", "DE" => "EUR", "YE" => "YER", "DZ" => "DZD", "US" => "USD", "UY" => "UYU", "YT" => "EUR", "UM" => "USD", "LB" => "LBP", "LC" => "XCD", "LA" => "LAK", "TV" => "AUD", "TW" => "TWD", "TT" => "TTD", "TR" => "TRY", "LK" => "LKR", "LI" => "CHF", "LV" => "EUR", "TO" => "TOP", "LT" => "LTL", "LU" => "EUR", "LR" => "LRD", "LS" => "LSL", "TH" => "THB", "TF" => "EUR", "TG" => "XOF", "TD" => "XAF", "TC" => "USD", "LY" => "LYD", "VA" => "EUR", "VC" => "XCD", "AE" => "AED", "AD" => "EUR", "AG" => "XCD", "AF" => "AFN", "AI" => "XCD", "VI" => "USD", "IS" => "ISK", "IR" => "IRR", "AM" => "AMD", "AL" => "ALL", "AO" => "AOA", "AQ" => "", "AS" => "USD", "AR" => "ARS", "AU" => "AUD", "AT" => "EUR", "AW" => "AWG", "IN" => "INR", "AX" => "EUR", "AZ" => "AZN", "IE" => "EUR", "ID" => "IDR", "UA" => "UAH", "QA" => "QAR", "MZ" => "MZN")





* Visibility: **public**
* This property is **static**.


### $continent

    public mixed $continent = array("AF" => array("country" => "Afghanistan", "continent" => "Asia"), "AX" => array("country" => "Åland Islands", "continent" => "Europe"), "AL" => array("country" => "Albania", "continent" => "Europe"), "DZ" => array("country" => "Algeria", "continent" => "Africa"), "AS" => array("country" => "American Samoa", "continent" => "Oceania"), "AD" => array("country" => "Andorra", "continent" => "Europe"), "AO" => array("country" => "Angola", "continent" => "Africa"), "AI" => array("country" => "Anguilla", "continent" => "North America"), "AQ" => array("country" => "Antarctica", "continent" => "Antarctica"), "AG" => array("country" => "Antigua and Barbuda", "continent" => "North America"), "AR" => array("country" => "Argentina", "continent" => "South America"), "AM" => array("country" => "Armenia", "continent" => "Asia"), "AW" => array("country" => "Aruba", "continent" => "North America"), "AU" => array("country" => "Australia", "continent" => "Oceania"), "AT" => array("country" => "Austria", "continent" => "Europe"), "AZ" => array("country" => "Azerbaijan", "continent" => "Asia"), "BS" => array("country" => "Bahamas", "continent" => "North America"), "BH" => array("country" => "Bahrain", "continent" => "Asia"), "BD" => array("country" => "Bangladesh", "continent" => "Asia"), "BB" => array("country" => "Barbados", "continent" => "North America"), "BY" => array("country" => "Belarus", "continent" => "Europe"), "BE" => array("country" => "Belgium", "continent" => "Europe"), "BZ" => array("country" => "Belize", "continent" => "North America"), "BJ" => array("country" => "Benin", "continent" => "Africa"), "BM" => array("country" => "Bermuda", "continent" => "North America"), "BT" => array("country" => "Bhutan", "continent" => "Asia"), "BO" => array("country" => "Bolivia", "continent" => "South America"), "BA" => array("country" => "Bosnia and Herzegovina", "continent" => "Europe"), "BW" => array("country" => "Botswana", "continent" => "Africa"), "BV" => array("country" => "Bouvet Island", "continent" => "Antarctica"), "BR" => array("country" => "Brazil", "continent" => "South America"), "IO" => array("country" => "British Indian Ocean Territory", "continent" => "Asia"), "BN" => array("country" => "Brunei Darussalam", "continent" => "Asia"), "BG" => array("country" => "Bulgaria", "continent" => "Europe"), "BF" => array("country" => "Burkina Faso", "continent" => "Africa"), "BI" => array("country" => "Burundi", "continent" => "Africa"), "KH" => array("country" => "Cambodia", "continent" => "Asia"), "CM" => array("country" => "Cameroon", "continent" => "Africa"), "CA" => array("country" => "Canada", "continent" => "North America"), "CV" => array("country" => "Cape Verde", "continent" => "Africa"), "KY" => array("country" => "Cayman Islands", "continent" => "North America"), "CF" => array("country" => "Central African Republic", "continent" => "Africa"), "TD" => array("country" => "Chad", "continent" => "Africa"), "CL" => array("country" => "Chile", "continent" => "South America"), "CN" => array("country" => "China", "continent" => "Asia"), "CX" => array("country" => "Christmas Island", "continent" => "Asia"), "CC" => array("country" => "Cocos (Keeling) Islands", "continent" => "Asia"), "CO" => array("country" => "Colombia", "continent" => "South America"), "KM" => array("country" => "Comoros", "continent" => "Africa"), "CG" => array("country" => "Congo", "continent" => "Africa"), "CD" => array("country" => "The Democratic Republic of The Congo", "continent" => "Africa"), "CK" => array("country" => "Cook Islands", "continent" => "Oceania"), "CR" => array("country" => "Costa Rica", "continent" => "North America"), "CI" => array("country" => "Cote D'ivoire", "continent" => "Africa"), "HR" => array("country" => "Croatia", "continent" => "Europe"), "CU" => array("country" => "Cuba", "continent" => "North America"), "CY" => array("country" => "Cyprus", "continent" => "Asia"), "CZ" => array("country" => "Czech Republic", "continent" => "Europe"), "DK" => array("country" => "Denmark", "continent" => "Europe"), "DJ" => array("country" => "Djibouti", "continent" => "Africa"), "DM" => array("country" => "Dominica", "continent" => "North America"), "DO" => array("country" => "Dominican Republic", "continent" => "North America"), "EC" => array("country" => "Ecuador", "continent" => "South America"), "EG" => array("country" => "Egypt", "continent" => "Africa"), "SV" => array("country" => "El Salvador", "continent" => "North America"), "GQ" => array("country" => "Equatorial Guinea", "continent" => "Africa"), "ER" => array("country" => "Eritrea", "continent" => "Africa"), "EE" => array("country" => "Estonia", "continent" => "Europe"), "ET" => array("country" => "Ethiopia", "continent" => "Africa"), "FK" => array("country" => "Falkland Islands (Malvinas)", "continent" => "South America"), "FO" => array("country" => "Faroe Islands", "continent" => "Europe"), "FJ" => array("country" => "Fiji", "continent" => "Oceania"), "FI" => array("country" => "Finland", "continent" => "Europe"), "FR" => array("country" => "France", "continent" => "Europe"), "GF" => array("country" => "French Guiana", "continent" => "South America"), "PF" => array("country" => "French Polynesia", "continent" => "Oceania"), "TF" => array("country" => "French Southern Territories", "continent" => "Antarctica"), "GA" => array("country" => "Gabon", "continent" => "Africa"), "GM" => array("country" => "Gambia", "continent" => "Africa"), "GE" => array("country" => "Georgia", "continent" => "Asia"), "DE" => array("country" => "Germany", "continent" => "Europe"), "GH" => array("country" => "Ghana", "continent" => "Africa"), "GI" => array("country" => "Gibraltar", "continent" => "Europe"), "GR" => array("country" => "Greece", "continent" => "Europe"), "GL" => array("country" => "Greenland", "continent" => "North America"), "GD" => array("country" => "Grenada", "continent" => "North America"), "GP" => array("country" => "Guadeloupe", "continent" => "North America"), "GU" => array("country" => "Guam", "continent" => "Oceania"), "GT" => array("country" => "Guatemala", "continent" => "North America"), "GG" => array("country" => "Guernsey", "continent" => "Europe"), "GN" => array("country" => "Guinea", "continent" => "Africa"), "GW" => array("country" => "Guinea-bissau", "continent" => "Africa"), "GY" => array("country" => "Guyana", "continent" => "South America"), "HT" => array("country" => "Haiti", "continent" => "North America"), "HM" => array("country" => "Heard Island and Mcdonald Islands", "continent" => "Antarctica"), "VA" => array("country" => "Holy See (Vatican City State)", "continent" => "Europe"), "HN" => array("country" => "Honduras", "continent" => "North America"), "HK" => array("country" => "Hong Kong", "continent" => "Asia"), "HU" => array("country" => "Hungary", "continent" => "Europe"), "IS" => array("country" => "Iceland", "continent" => "Europe"), "IN" => array("country" => "India", "continent" => "Asia"), "ID" => array("country" => "Indonesia", "continent" => "Asia"), "IR" => array("country" => "Iran", "continent" => "Asia"), "IQ" => array("country" => "Iraq", "continent" => "Asia"), "IE" => array("country" => "Ireland", "continent" => "Europe"), "IM" => array("country" => "Isle of Man", "continent" => "Europe"), "IL" => array("country" => "Israel", "continent" => "Asia"), "IT" => array("country" => "Italy", "continent" => "Europe"), "JM" => array("country" => "Jamaica", "continent" => "North America"), "JP" => array("country" => "Japan", "continent" => "Asia"), "JE" => array("country" => "Jersey", "continent" => "Europe"), "JO" => array("country" => "Jordan", "continent" => "Asia"), "KZ" => array("country" => "Kazakhstan", "continent" => "Asia"), "KE" => array("country" => "Kenya", "continent" => "Africa"), "KI" => array("country" => "Kiribati", "continent" => "Oceania"), "KP" => array("country" => "Democratic People's Republic of Korea", "continent" => "Asia"), "KR" => array("country" => "Republic of Korea", "continent" => "Asia"), "KW" => array("country" => "Kuwait", "continent" => "Asia"), "KG" => array("country" => "Kyrgyzstan", "continent" => "Asia"), "LA" => array("country" => "Lao People's Democratic Republic", "continent" => "Asia"), "LV" => array("country" => "Latvia", "continent" => "Europe"), "LB" => array("country" => "Lebanon", "continent" => "Asia"), "LS" => array("country" => "Lesotho", "continent" => "Africa"), "LR" => array("country" => "Liberia", "continent" => "Africa"), "LY" => array("country" => "Libya", "continent" => "Africa"), "LI" => array("country" => "Liechtenstein", "continent" => "Europe"), "LT" => array("country" => "Lithuania", "continent" => "Europe"), "LU" => array("country" => "Luxembourg", "continent" => "Europe"), "MO" => array("country" => "Macao", "continent" => "Asia"), "MK" => array("country" => "Macedonia", "continent" => "Europe"), "MG" => array("country" => "Madagascar", "continent" => "Africa"), "MW" => array("country" => "Malawi", "continent" => "Africa"), "MY" => array("country" => "Malaysia", "continent" => "Asia"), "MV" => array("country" => "Maldives", "continent" => "Asia"), "ML" => array("country" => "Mali", "continent" => "Africa"), "MT" => array("country" => "Malta", "continent" => "Europe"), "MH" => array("country" => "Marshall Islands", "continent" => "Oceania"), "MQ" => array("country" => "Martinique", "continent" => "North America"), "MR" => array("country" => "Mauritania", "continent" => "Africa"), "MU" => array("country" => "Mauritius", "continent" => "Africa"), "YT" => array("country" => "Mayotte", "continent" => "Africa"), "MX" => array("country" => "Mexico", "continent" => "North America"), "FM" => array("country" => "Micronesia", "continent" => "Oceania"), "MD" => array("country" => "Moldova", "continent" => "Europe"), "MC" => array("country" => "Monaco", "continent" => "Europe"), "MN" => array("country" => "Mongolia", "continent" => "Asia"), "ME" => array("country" => "Montenegro", "continent" => "Europe"), "MS" => array("country" => "Montserrat", "continent" => "North America"), "MA" => array("country" => "Morocco", "continent" => "Africa"), "MZ" => array("country" => "Mozambique", "continent" => "Africa"), "MM" => array("country" => "Myanmar", "continent" => "Asia"), "NA" => array("country" => "Namibia", "continent" => "Africa"), "NR" => array("country" => "Nauru", "continent" => "Oceania"), "NP" => array("country" => "Nepal", "continent" => "Asia"), "NL" => array("country" => "Netherlands", "continent" => "Europe"), "AN" => array("country" => "Netherlands Antilles", "continent" => "North America"), "NC" => array("country" => "New Caledonia", "continent" => "Oceania"), "NZ" => array("country" => "New Zealand", "continent" => "Oceania"), "NI" => array("country" => "Nicaragua", "continent" => "North America"), "NE" => array("country" => "Niger", "continent" => "Africa"), "NG" => array("country" => "Nigeria", "continent" => "Africa"), "NU" => array("country" => "Niue", "continent" => "Oceania"), "NF" => array("country" => "Norfolk Island", "continent" => "Oceania"), "MP" => array("country" => "Northern Mariana Islands", "continent" => "Oceania"), "NO" => array("country" => "Norway", "continent" => "Europe"), "OM" => array("country" => "Oman", "continent" => "Asia"), "PK" => array("country" => "Pakistan", "continent" => "Asia"), "PW" => array("country" => "Palau", "continent" => "Oceania"), "PS" => array("country" => "Palestinia", "continent" => "Asia"), "PA" => array("country" => "Panama", "continent" => "North America"), "PG" => array("country" => "Papua New Guinea", "continent" => "Oceania"), "PY" => array("country" => "Paraguay", "continent" => "South America"), "PE" => array("country" => "Peru", "continent" => "South America"), "PH" => array("country" => "Philippines", "continent" => "Asia"), "PN" => array("country" => "Pitcairn", "continent" => "Oceania"), "PL" => array("country" => "Poland", "continent" => "Europe"), "PT" => array("country" => "Portugal", "continent" => "Europe"), "PR" => array("country" => "Puerto Rico", "continent" => "North America"), "QA" => array("country" => "Qatar", "continent" => "Asia"), "RE" => array("country" => "Reunion", "continent" => "Africa"), "RO" => array("country" => "Romania", "continent" => "Europe"), "RU" => array("country" => "Russian Federation", "continent" => "Europe"), "RW" => array("country" => "Rwanda", "continent" => "Africa"), "SH" => array("country" => "Saint Helena", "continent" => "Africa"), "KN" => array("country" => "Saint Kitts and Nevis", "continent" => "North America"), "LC" => array("country" => "Saint Lucia", "continent" => "North America"), "PM" => array("country" => "Saint Pierre and Miquelon", "continent" => "North America"), "VC" => array("country" => "Saint Vincent and The Grenadines", "continent" => "North America"), "WS" => array("country" => "Samoa", "continent" => "Oceania"), "SM" => array("country" => "San Marino", "continent" => "Europe"), "ST" => array("country" => "Sao Tome and Principe", "continent" => "Africa"), "SA" => array("country" => "Saudi Arabia", "continent" => "Asia"), "SN" => array("country" => "Senegal", "continent" => "Africa"), "RS" => array("country" => "Serbia", "continent" => "Europe"), "SC" => array("country" => "Seychelles", "continent" => "Africa"), "SL" => array("country" => "Sierra Leone", "continent" => "Africa"), "SG" => array("country" => "Singapore", "continent" => "Asia"), "SK" => array("country" => "Slovakia", "continent" => "Europe"), "SI" => array("country" => "Slovenia", "continent" => "Europe"), "SB" => array("country" => "Solomon Islands", "continent" => "Oceania"), "SO" => array("country" => "Somalia", "continent" => "Africa"), "ZA" => array("country" => "South Africa", "continent" => "Africa"), "GS" => array("country" => "South Georgia and The South Sandwich Islands", "continent" => "Antarctica"), "ES" => array("country" => "Spain", "continent" => "Europe"), "LK" => array("country" => "Sri Lanka", "continent" => "Asia"), "SD" => array("country" => "Sudan", "continent" => "Africa"), "SR" => array("country" => "Suriname", "continent" => "South America"), "SJ" => array("country" => "Svalbard and Jan Mayen", "continent" => "Europe"), "SZ" => array("country" => "Swaziland", "continent" => "Africa"), "SE" => array("country" => "Sweden", "continent" => "Europe"), "CH" => array("country" => "Switzerland", "continent" => "Europe"), "SY" => array("country" => "Syrian Arab Republic", "continent" => "Asia"), "TW" => array("country" => "Taiwan, Province of China", "continent" => "Asia"), "TJ" => array("country" => "Tajikistan", "continent" => "Asia"), "TZ" => array("country" => "Tanzania, United Republic of", "continent" => "Africa"), "TH" => array("country" => "Thailand", "continent" => "Asia"), "TL" => array("country" => "Timor-leste", "continent" => "Asia"), "TG" => array("country" => "Togo", "continent" => "Africa"), "TK" => array("country" => "Tokelau", "continent" => "Oceania"), "TO" => array("country" => "Tonga", "continent" => "Oceania"), "TT" => array("country" => "Trinidad and Tobago", "continent" => "North America"), "TN" => array("country" => "Tunisia", "continent" => "Africa"), "TR" => array("country" => "Turkey", "continent" => "Asia"), "TM" => array("country" => "Turkmenistan", "continent" => "Asia"), "TC" => array("country" => "Turks and Caicos Islands", "continent" => "North America"), "TV" => array("country" => "Tuvalu", "continent" => "Oceania"), "UG" => array("country" => "Uganda", "continent" => "Africa"), "UA" => array("country" => "Ukraine", "continent" => "Europe"), "AE" => array("country" => "United Arab Emirates", "continent" => "Asia"), "GB" => array("country" => "United Kingdom", "continent" => "Europe"), "US" => array("country" => "United States", "continent" => "North America"), "UM" => array("country" => "United States Minor Outlying Islands", "continent" => "Oceania"), "UY" => array("country" => "Uruguay", "continent" => "South America"), "UZ" => array("country" => "Uzbekistan", "continent" => "Asia"), "VU" => array("country" => "Vanuatu", "continent" => "Oceania"), "VE" => array("country" => "Venezuela", "continent" => "South America"), "VN" => array("country" => "Vietnam", "continent" => "Asia"), "VG" => array("country" => "Virgin Islands, British", "continent" => "North America"), "VI" => array("country" => "Virgin Islands, U.S.", "continent" => "North America"), "WF" => array("country" => "Wallis and Futuna", "continent" => "Oceania"), "EH" => array("country" => "Western Sahara", "continent" => "Africa"), "YE" => array("country" => "Yemen", "continent" => "Asia"), "ZM" => array("country" => "Zambia", "continent" => "Africa"), "ZW" => array("country" => "Zimbabwe", "continent" => "Africa"))





* Visibility: **public**
* This property is **static**.


### $hasOne

    public mixed $hasOne = array('Franchisees' => array('key' => array('franchisee_id' => 'id')), 'Agreements' => array('key' => array('agreement_id' => 'id')))





* Visibility: **public**


Methods
-------


### cpi_percentage

    mixed app\models\FranchiseeAgreements::cpi_percentage()





* Visibility: **public**
* This method is **static**.




### franchiseeAgreementsReport

    mixed app\models\FranchiseeAgreements::franchiseeAgreementsReport($country, $ctc, $nc)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $country **mixed**
* $ctc **mixed**
* $nc **mixed**



### countGroupNames

    mixed app\models\FranchiseeAgreements::countGroupNames()





* Visibility: **public**
* This method is **static**.




### countNoGroupNames

    mixed app\models\FranchiseeAgreements::countNoGroupNames()





* Visibility: **public**
* This method is **static**.




### filtered_export

    mixed app\models\FranchiseeAgreements::filtered_export($state)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $state **mixed**



### export

    mixed app\models\FranchiseeAgreements::export()





* Visibility: **public**
* This method is **static**.




### listAllAgreements

    mixed app\models\FranchiseeAgreements::listAllAgreements()





* Visibility: **public**
* This method is **static**.




### countAgreements

    mixed app\models\FranchiseeAgreements::countAgreements()





* Visibility: **public**
* This method is **static**.




### oldest

    mixed app\models\FranchiseeAgreements::oldest()





* Visibility: **public**
* This method is **static**.




### sold_studios_this_month

    mixed app\models\FranchiseeAgreements::sold_studios_this_month()





* Visibility: **public**
* This method is **static**.




### sold_studios_this_month_per_day

    mixed app\models\FranchiseeAgreements::sold_studios_this_month_per_day()





* Visibility: **public**
* This method is **static**.




### sold_studios_by_country_this_month

    mixed app\models\FranchiseeAgreements::sold_studios_by_country_this_month()





* Visibility: **public**
* This method is **static**.



