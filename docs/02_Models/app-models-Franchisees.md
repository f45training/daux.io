app\models\Franchisees
===============






* Class name: Franchisees
* Namespace: app\models
* Parent class: lithium\data\Model





Properties
----------


### $statuses

    public mixed $statuses = array('1' => 'Functioning Now', '2' => 'Functioning Soon', '3' => 'Opening Date Set', '4' => 'Opening Date Actual')





* Visibility: **public**
* This property is **static**.


### $hqChecklist

    public mixed $hqChecklist = array('F45 Equipment Used', 'Signage Approved', 'All Trainers passed and inducted')





* Visibility: **public**
* This property is **static**.


### $statusChecklist

    public mixed $statusChecklist = array(array('index' => '0', 'name' => 'Induction', 'description' => 'Facebook page access', 'text' => 'Attending the HQ week long induction training is compulsory. You will not be granted access to order
              equipment etc if this is not completed and is imperative, as  you will learn how to operate your studio.'), array('index' => '1', 'name' => 'Premise, Location + Lease Approval', 'description' => 'Equipment Ordered Access', 'text' => 'Your premise must be approved by HQ. It must be rectangle, 180m2/2,000 sq feet and located in your
            exclusive territory. Without this approval you run the risk of not being approved to open your studio.'), array('index' => '2', 'name' => 'Equipment Ordered', 'description' => 'Website Activation', 'text' => 'You are required to order your equipment from HQ. Your studio will not be approved to open if
            you do not acquire the F45 equipment.'), array('index' => '3', 'name' => 'Floorplan Approval', 'description' => 'Instagram and Equipment Order Access', 'text' => 'Your floor plan must be approved by HQ as the workouts will not operate if you do not put the chin up bars,
            toilets and sled tracks in the location.'), array('index' => '4', 'name' => 'Signage Design + Install Approval', 'description' => 'Can Order Uniforms', 'text' => 'You  will obtain signage approval prior to installation so that you are compliantwith the brand
            guidelines. Once you have installed the signage you will upload the photos to gain final approval on this step.'), array('index' => '5', 'name' => 'Pre-Open Inspection', 'description' => 'F45TV Access', 'text' => 'This is the final step you need to take prior to opening. Signage,layout and equipment is all cross checked for the
             last time prior toyou being granted approval to open.'), array('index' => '6', 'name' => 'Functioning Now', 'description' => 'Check if now functioning'))





* Visibility: **public**
* This property is **static**.


### $statusChecklistSubitems

    public mixed $statusChecklistSubitems = array('1' => array(array('index' => '0', 'name' => 'Site Approved', 'description' => 'Lease Approval'), array('index' => '1', 'name' => 'Lease Approved', 'description' => 'Premise, Location + Lease Approval'), array('index' => '2', 'name' => 'Draft Lease Approved', 'description' => 'Draft Lease Approval')), '4' => array(array('index' => '0', 'name' => 'Signage Design Approved', 'description' => 'Signage Design + Install Approval')))





* Visibility: **public**
* This property is **static**.


### $statusChecklistSubitems_3

    public mixed $statusChecklistSubitems_3 = array('3' => array(array('index' => '3', 'name' => 'Flooring Size', 'field_name' => 'net_training_area', 'description' => '(Please input square meters/square foot for US)', 'sub_value' => 'net_training_area_unit', 'values' => array('sqm', 'sq ft')), array('index' => '3', 'name' => 'Sled Track Length', 'field_name' => 'sled_track_length', 'description' => '(Please input square meters)')))





* Visibility: **public**
* This property is **static**.


### $regions

    public mixed $regions = array('Africa', 'Asia', 'Europe', 'North America', 'Oceania', 'South America')





* Visibility: **public**
* This property is **static**.


### $countryList

    public mixed $countryList = array("AF" => "Afghanistan", "AL" => "Albania", "DZ" => "Algeria", "AS" => "American Samoa", "AD" => "Andorra", "AO" => "Angola", "AI" => "Anguilla", "AQ" => "Antarctica", "AG" => "Antigua and Barbuda", "AR" => "Argentina", "AM" => "Armenia", "AW" => "Aruba", "AU" => "Australia", "AT" => "Austria", "AZ" => "Azerbaijan", "BS" => "Bahamas", "BH" => "Bahrain", "BD" => "Bangladesh", "BB" => "Barbados", "BY" => "Belarus", "BE" => "Belgium", "BZ" => "Belize", "BJ" => "Benin", "BM" => "Bermuda", "BT" => "Bhutan", "BO" => "Bolivia", "BA" => "Bosnia and Herzegovina", "BW" => "Botswana", "BV" => "Bouvet Island", "BR" => "Brazil", "BQ" => "British Antarctic Territory", "IO" => "British Indian Ocean Territory", "VG" => "British Virgin Islands", "BN" => "Brunei", "BG" => "Bulgaria", "BF" => "Burkina Faso", "BI" => "Burundi", "KH" => "Cambodia", "CM" => "Cameroon", "CA" => "Canada", "CT" => "Canton and Enderbury Islands", "CV" => "Cape Verde", "KY" => "Cayman Islands", "CF" => "Central African Republic", "TD" => "Chad", "CL" => "Chile", "CN" => "China", "CX" => "Christmas Island", "CC" => "Cocos [Keeling] Islands", "CO" => "Colombia", "KM" => "Comoros", "CG" => "Congo - Brazzaville", "CD" => "Congo - Kinshasa", "CK" => "Cook Islands", "CR" => "Costa Rica", "HR" => "Croatia", "CU" => "Cuba", "CY" => "Cyprus", "CZ" => "Czech Republic", "CI" => "Côte d’Ivoire", "DK" => "Denmark", "DJ" => "Djibouti", "DM" => "Dominica", "DO" => "Dominican Republic", "NQ" => "Dronning Maud Land", "DD" => "East Germany", "EC" => "Ecuador", "EG" => "Egypt", "SV" => "El Salvador", "GQ" => "Equatorial Guinea", "ER" => "Eritrea", "EE" => "Estonia", "ET" => "Ethiopia", "FK" => "Falkland Islands", "FO" => "Faroe Islands", "FJ" => "Fiji", "FI" => "Finland", "FR" => "France", "GF" => "French Guiana", "PF" => "French Polynesia", "TF" => "French Southern Territories", "FQ" => "French Southern and Antarctic Territories", "GA" => "Gabon", "GM" => "Gambia", "GE" => "Georgia", "DE" => "Germany", "GH" => "Ghana", "GI" => "Gibraltar", "GR" => "Greece", "GL" => "Greenland", "GD" => "Grenada", "GP" => "Guadeloupe", "GU" => "Guam", "GT" => "Guatemala", "GG" => "Guernsey", "GN" => "Guinea", "GW" => "Guinea-Bissau", "GY" => "Guyana", "HT" => "Haiti", "HM" => "Heard Island and McDonald Islands", "HN" => "Honduras", "HK" => "Hong Kong", "HU" => "Hungary", "IS" => "Iceland", "IN" => "India", "ID" => "Indonesia", "IR" => "Iran", "IQ" => "Iraq", "IE" => "Ireland", "IM" => "Isle of Man", "IL" => "Israel", "IT" => "Italy", "JM" => "Jamaica", "JP" => "Japan", "JE" => "Jersey", "JT" => "Johnston Island", "JO" => "Jordan", "KZ" => "Kazakhstan", "KE" => "Kenya", "KI" => "Kiribati", "KW" => "Kuwait", "KG" => "Kyrgyzstan", "LA" => "Laos", "LV" => "Latvia", "LB" => "Lebanon", "LS" => "Lesotho", "LR" => "Liberia", "LY" => "Libya", "LI" => "Liechtenstein", "LT" => "Lithuania", "LU" => "Luxembourg", "MO" => "Macau SAR China", "MK" => "Macedonia", "MG" => "Madagascar", "MW" => "Malawi", "MY" => "Malaysia", "MV" => "Maldives", "ML" => "Mali", "MT" => "Malta", "MH" => "Marshall Islands", "MQ" => "Martinique", "MR" => "Mauritania", "MU" => "Mauritius", "YT" => "Mayotte", "FX" => "Metropolitan France", "MX" => "Mexico", "FM" => "Micronesia", "MI" => "Midway Islands", "MD" => "Moldova", "MC" => "Monaco", "MN" => "Mongolia", "ME" => "Montenegro", "MS" => "Montserrat", "MA" => "Morocco", "MZ" => "Mozambique", "MM" => "Myanmar [Burma]", "NA" => "Namibia", "NR" => "Nauru", "NP" => "Nepal", "NL" => "Netherlands", "AN" => "Netherlands Antilles", "NT" => "Neutral Zone", "NC" => "New Caledonia", "NZ" => "New Zealand", "NI" => "Nicaragua", "NE" => "Niger", "NG" => "Nigeria", "NU" => "Niue", "NF" => "Norfolk Island", "KP" => "North Korea", "VD" => "North Vietnam", "MP" => "Northern Mariana Islands", "NO" => "Norway", "OM" => "Oman", "PC" => "Pacific Islands Trust Territory", "PK" => "Pakistan", "PW" => "Palau", "PS" => "Palestinian Territories", "PA" => "Panama", "PZ" => "Panama Canal Zone", "PG" => "Papua New Guinea", "PY" => "Paraguay", "YD" => "People's Democratic Republic of Yemen", "PE" => "Peru", "PH" => "Philippines", "PN" => "Pitcairn Islands", "PL" => "Poland", "PT" => "Portugal", "PR" => "Puerto Rico", "QA" => "Qatar", "RO" => "Romania", "RU" => "Russia", "RW" => "Rwanda", "RE" => "Réunion", "BL" => "Saint Barthélemy", "SH" => "Saint Helena", "KN" => "Saint Kitts and Nevis", "LC" => "Saint Lucia", "MF" => "Saint Martin", "PM" => "Saint Pierre and Miquelon", "VC" => "Saint Vincent and the Grenadines", "WS" => "Samoa", "SM" => "San Marino", "SA" => "Saudi Arabia", "SN" => "Senegal", "RS" => "Serbia", "CS" => "Serbia and Montenegro", "SC" => "Seychelles", "SL" => "Sierra Leone", "SG" => "Singapore", "SK" => "Slovakia", "SI" => "Slovenia", "SB" => "Solomon Islands", "SO" => "Somalia", "ZA" => "South Africa", "GS" => "South Georgia and the South Sandwich Islands", "KR" => "South Korea", "ES" => "Spain", "LK" => "Sri Lanka", "SD" => "Sudan", "SR" => "Suriname", "SJ" => "Svalbard and Jan Mayen", "SZ" => "Swaziland", "SE" => "Sweden", "CH" => "Switzerland", "SY" => "Syria", "ST" => "São Tomé and Príncipe", "TW" => "Taiwan", "TJ" => "Tajikistan", "TZ" => "Tanzania", "TH" => "Thailand", "TL" => "Timor-Leste", "TG" => "Togo", "TK" => "Tokelau", "TO" => "Tonga", "TT" => "Trinidad and Tobago", "TN" => "Tunisia", "TR" => "Turkey", "TM" => "Turkmenistan", "TC" => "Turks and Caicos Islands", "TV" => "Tuvalu", "UM" => "U.S. Minor Outlying Islands", "PU" => "U.S. Miscellaneous Pacific Islands", "VI" => "U.S. Virgin Islands", "UG" => "Uganda", "UA" => "Ukraine", "SU" => "Union of Soviet Socialist Republics", "AE" => "United Arab Emirates", "GB" => "United Kingdom", "US" => "United States", "ZZ" => "Unknown or Invalid Region", "UY" => "Uruguay", "UZ" => "Uzbekistan", "VU" => "Vanuatu", "VA" => "Vatican City", "VE" => "Venezuela", "VN" => "Vietnam", "WK" => "Wake Island", "WF" => "Wallis and Futuna", "EH" => "Western Sahara", "YE" => "Yemen", "ZM" => "Zambia", "ZW" => "Zimbabwe", "AX" => "Åland Islands", "CAM" => "Campus", "COR" => "Corporate", "COL" => "College", "MIL" => "Military", "GOV" => "Government", "FRA" => "Franchisee", "HSL" => "High School")





* Visibility: **public**
* This property is **static**.


### $countryCode

    public mixed $countryCode = array('ANDORRA' => '376', 'UNITED ARAB EMIRATES' => '971', 'AFGHANISTAN' => '93', 'ANTIGUA AND BARBUDA' => '1268', 'ANGUILLA' => '1264', 'ALBANIA' => '355', 'ARMENIA' => '374', 'NETHERLANDS ANTILLES' => '599', 'ANGOLA' => '244', 'ANTARCTICA' => '672', 'ARGENTINA' => '54', 'AMERICAN SAMOA' => '1684', 'AUSTRIA' => '43', 'AUSTRALIA' => '61', 'ARUBA' => '297', 'AZERBAIJAN' => '994', 'BOSNIA AND HERZEGOVINA' => '387', 'BARBADOS' => '1246', 'BANGLADESH' => '880', 'BELGIUM' => '32', 'BURKINA FASO' => '226', 'BULGARIA' => '359', 'BAHRAIN' => '973', 'BURUNDI' => '257', 'BENIN' => '229', 'SAINT BARTHELEMY' => '590', 'BERMUDA' => '1441', 'BRUNEI DARUSSALAM' => '673', 'BOLIVIA' => '591', 'BRAZIL' => '55', 'BAHAMAS' => '1242', 'BHUTAN' => '975', 'BOTSWANA' => '267', 'BELARUS' => '375', 'BELIZE' => '501', 'CANADA' => '1', 'COCOS (KEELING ISLANDS' => '61', 'CONGO, THE DEMOCRATIC REPUBLIC OF THE' => '243', 'CENTRAL AFRICAN REPUBLIC' => '236', 'CONGO' => '242', 'SWITZERLAND' => '41', 'COTE D IVOIRE' => '225', 'COOK ISLANDS' => '682', 'CHILE' => '56', 'CAMEROON' => '237', 'CHINA' => '86', 'COLOMBIA' => '57', 'COSTA RICA' => '506', 'CUBA' => '53', 'CAPE VERDE' => '238', 'CHRISTMAS ISLAND' => '61', 'CYPRUS' => '357', 'CZECH REPUBLIC' => '420', 'GERMANY' => '49', 'DJIBOUTI' => '253', 'DENMARK' => '45', 'DOMINICA' => '1767', 'DOMINICAN REPUBLIC' => '1809', 'ALGERIA' => '213', 'ECUADOR' => '593', 'ESTONIA' => '372', 'EGYPT' => '20', 'ERITREA' => '291', 'SPAIN' => '34', 'ETHIOPIA' => '251', 'FINLAND' => '358', 'FIJI' => '679', 'FALKLAND ISLANDS (MALVINAS' => '500', 'MICRONESIA, FEDERATED STATES OF' => '691', 'FAROE ISLANDS' => '298', 'FRANCE' => '33', 'GABON' => '241', 'UNITED KINGDOM' => '44', 'GRENADA' => '1473', 'GEORGIA' => '995', 'GHANA' => '233', 'GIBRALTAR' => '350', 'GREENLAND' => '299', 'GAMBIA' => '220', 'GUINEA' => '224', 'EQUATORIAL GUINEA' => '240', 'GREECE' => '30', 'GUATEMALA' => '502', 'GUAM' => '1671', 'GUINEA-BISSAU' => '245', 'GUYANA' => '592', 'HONG KONG' => '852', 'HONDURAS' => '504', 'CROATIA' => '385', 'HAITI' => '509', 'HUNGARY' => '36', 'INDONESIA' => '62', 'IRELAND' => '353', 'ISRAEL' => '972', 'ISLE OF MAN' => '44', 'INDIA' => '91', 'IRAQ' => '964', 'IRAN, ISLAMIC REPUBLIC OF' => '98', 'ICELAND' => '354', 'ITALY' => '39', 'JAMAICA' => '1876', 'JORDAN' => '962', 'JAPAN' => '81', 'KENYA' => '254', 'KYRGYZSTAN' => '996', 'CAMBODIA' => '855', 'KIRIBATI' => '686', 'COMOROS' => '269', 'SAINT KITTS AND NEVIS' => '1869', 'KOREA DEMOCRATIC PEOPLES REPUBLIC OF' => '850', 'KOREA REPUBLIC OF' => '82', 'KUWAIT' => '965', 'CAYMAN ISLANDS' => '1345', 'KAZAKSTAN' => '7', 'LAO PEOPLES DEMOCRATIC REPUBLIC' => '856', 'LEBANON' => '961', 'SAINT LUCIA' => '1758', 'LIECHTENSTEIN' => '423', 'SRI LANKA' => '94', 'LIBERIA' => '231', 'LESOTHO' => '266', 'LITHUANIA' => '370', 'LUXEMBOURG' => '352', 'LATVIA' => '371', 'LIBYAN ARAB JAMAHIRIYA' => '218', 'MOROCCO' => '212', 'MONACO' => '377', 'MOLDOVA, REPUBLIC OF' => '373', 'MONTENEGRO' => '382', 'SAINT MARTIN' => '1599', 'MADAGASCAR' => '261', 'MARSHALL ISLANDS' => '692', 'MACEDONIA, THE FORMER YUGOSLAV REPUBLIC OF' => '389', 'MALI' => '223', 'MYANMAR' => '95', 'MONGOLIA' => '976', 'MACAU' => '853', 'NORTHERN MARIANA ISLANDS' => '1670', 'MAURITANIA' => '222', 'MONTSERRAT' => '1664', 'MALTA' => '356', 'MAURITIUS' => '230', 'MALDIVES' => '960', 'MALAWI' => '265', 'MEXICO' => '52', 'MALAYSIA' => '60', 'MOZAMBIQUE' => '258', 'NAMIBIA' => '264', 'NEW CALEDONIA' => '687', 'NIGER' => '227', 'NIGERIA' => '234', 'NICARAGUA' => '505', 'NETHERLANDS' => '31', 'NORWAY' => '47', 'NEPAL' => '977', 'NAURU' => '674', 'NIUE' => '683', 'NEW ZEALAND' => '64', 'OMAN' => '968', 'PANAMA' => '507', 'PERU' => '51', 'FRENCH POLYNESIA' => '689', 'PAPUA NEW GUINEA' => '675', 'PHILIPPINES' => '63', 'PAKISTAN' => '92', 'POLAND' => '48', 'SAINT PIERRE AND MIQUELON' => '508', 'PITCAIRN' => '870', 'PUERTO RICO' => '1', 'PORTUGAL' => '351', 'PALAU' => '680', 'PARAGUAY' => '595', 'QATAR' => '974', 'ROMANIA' => '40', 'SERBIA' => '381', 'RUSSIAN FEDERATION' => '7', 'RWANDA' => '250', 'SAUDI ARABIA' => '966', 'SOLOMON ISLANDS' => '677', 'SEYCHELLES' => '248', 'SUDAN' => '249', 'SWEDEN' => '46', 'SINGAPORE' => '65', 'SAINT HELENA' => '290', 'SLOVENIA' => '386', 'SLOVAKIA' => '421', 'SIERRA LEONE' => '232', 'SAN MARINO' => '378', 'SENEGAL' => '221', 'SOMALIA' => '252', 'SURINAME' => '597', 'SAO TOME AND PRINCIPE' => '239', 'EL SALVADOR' => '503', 'SYRIAN ARAB REPUBLIC' => '963', 'SWAZILAND' => '268', 'TURKS AND CAICOS ISLANDS' => '1649', 'CHAD' => '235', 'TOGO' => '228', 'THAILAND' => '66', 'TAJIKISTAN' => '992', 'TOKELAU' => '690', 'TIMOR-LESTE' => '670', 'TURKMENISTAN' => '993', 'TUNISIA' => '216', 'TONGA' => '676', 'TURKEY' => '90', 'TRINIDAD AND TOBAGO' => '1868', 'TUVALU' => '688', 'TAIWAN, PROVINCE OF CHINA' => '886', 'TANZANIA, UNITED REPUBLIC OF' => '255', 'UKRAINE' => '380', 'UGANDA' => '256', 'UNITED STATES' => '1', 'URUGUAY' => '598', 'UZBEKISTAN' => '998', 'HOLY SEE (VATICAN CITY STATE' => '39', 'SAINT VINCENT AND THE GRENADINES' => '1784', 'VENEZUELA' => '58', 'VIRGIN ISLANDS, BRITISH' => '1284', 'VIRGIN ISLANDS, U.S.' => '1340', 'VIET NAM' => '84', 'VANUATU' => '678', 'WALLIS AND FUTUNA' => '681', 'SAMOA' => '685', 'KOSOVO' => '381', 'YEMEN' => '967', 'MAYOTTE' => '262', 'SOUTH AFRICA' => '27', 'ZAMBIA' => '260', 'ZIMBABWE' => '263')





* Visibility: **public**
* This property is **static**.


### $_schema

    protected mixed $_schema = array('id' => 'integer', 'access_code' => 'string', 'name' => 'string', 'location' => 'string', 'f45tv_version' => 'string', 'week' => 'integer', 'weekday' => 'integer', 'average_review_score' => 'float', 'leaderboard_position' => 'integer', 'status' => 'integer', 'timestamp' => 'timestamp', 'weekday_updated_on' => 'date', 'deployed' => 'integer', 'local_ip' => 'string', 'email' => 'string', 'facebookurl' => 'string', 'phone' => 'string', 'instagramname' => 'string', 'country' => 'string', 'region' => 'string', 'state' => 'string', 'instagram_pass' => 'string', 'latitude' => 'string', 'longitude' => 'string', 'test_studio' => 'string', 'expected_opening_on' => 'date', 'grand_opening_date' => 'date', 'hq_checklist' => 'string', 'status_checklist' => 'string', 'status_checklist_subitems' => 'text', 'on_boarded' => 'boolean', 'on_boarded_date' => 'date', 'online_training_complete' => 'boolean', 'mindbody_id' => 'integer', 'show_upgrade_notice' => 'boolean', 'change_playbook_schedule' => 'boolean', 'allow_timeline_selection' => 'boolean', 'f45tv_demo_mode' => 'string', 'admin_access' => 'string', 'compliance_answers' => 'text', 'updated_at' => 'datetime', 'timezone' => 'string', 'slug' => 'string', 'division_channel' => 'integer', 'studio_channel' => 'integer', 'division_number' => 'integer', 'social_checked_at' => 'integer', 'is_admin' => 'boolean', 'size_workout_area' => 'integer', 'size_workout_area_unit' => 'string', 'toilet_number' => 'integer', 'shower_number' => 'integer', 'net_training_area' => 'integer', 'net_training_area_unit' => 'string', 'ceiling_height_area_width' => 'integer', 'ceiling_height_area_width_unit' => 'string', 'net_training_area_width' => 'integer', 'net_training_area_width_unit' => 'string', 'is_agree_preloc' => 'boolean', 'is_acknowledge_preloc' => 'boolean', 'location_level' => 'string', 'is_main_road' => 'integer', 'property_type' => 'string', 'property_age' => 'string', 'is_near_border' => 'integer', 'is_single_level_floor' => 'integer', 'has_premise_bearing' => 'integer', 'f45fm_enabled' => 'boolean', 'lionheart_enabled' => 'boolean', 'billboard_enabled' => 'boolean', 'movement_enabled' => 'boolean', 'schedule_enabled' => 'boolean', 'use_alternative_exercise' => 'boolean', 'insurance_approved' => 'boolean', 'trainers_certified' => 'boolean', 'healcode' => 'string', 'healcode2' => 'string', 'healcode3' => 'string', 'healcode4' => 'string', 'tncagreed' => 'timestamp', 'useridtncagree' => 'integer', 'display_address' => 'string', 'studio_send_email' => 'boolean', 'is_show_compliance' => 'boolean', 'preopen_send_email' => 'boolean', 'preopen_email_sentat' => 'timestamp', 'is_debug' => 'boolean', 'is_deleted' => 'boolean', 'franchisee_type' => 'string', 'franchisee_type_id' => 'integer', 'timeline_version' => 'string', 'membership_join_button_text' => 'string', 'is_islamic_state' => 'boolean', 'admin_notes' => 'text', 'is_sent_f45tv_starter_pack' => 'boolean', 'f45tv_starter_pack_sent_date' => 'date', 'f45tv_starter_pack_order_number' => 'string', 'is_all_internal' => 'boolean', 'is_photo_accepted' => 'boolean', 'loc_notes' => 'string', 'can_move_station' => 'boolean', 'admin_access_date' => 'date', 'is_admin_date' => 'date', 'is_playoffs_allowed' => 'boolean', 'postcard_sent_at' => 'date', 'is_multiple_ip' => 'boolean', 'in_advance' => 'integer', 'new_signup_process' => 'string', 'pre_open_marketing_spend' => 'float', 'is_paid_pre_open_marketing_spend' => 'boolean', 'f45fm_screen' => 'integer', 'is_minimize_overdue_popup' => 'boolean', 'flooring_size' => 'integer', 'sled_track_length' => 'integer', 'is_marketing_enabled' => 'boolean', 'can_completely_change_schedule' => 'boolean', 'draft_sqft_annum' => 'string', 'draft_total_size_premise' => 'integer', 'draft_term_renewals' => 'string', 'draft_rent_free' => 'integer', 'draft_tenant_incentives' => 'boolean', 'draft_contribution' => 'string', 'facebook_pixel_id' => 'string', 'google_analytics_id' => 'string', 'f45tv_error_message' => 'string', 'shipping_reciever_first_name' => 'string', 'shipping_reciever_last_name' => 'string', 'shipping_email' => 'string', 'shipping_phone_number' => 'string', 'shipping_address_line_1' => 'string', 'shipping_address_line_2' => 'string', 'shipping_city' => 'string', 'shipping_state' => 'string', 'shipping_postcode' => 'string', 'shipping_country' => 'string', 'shipping_special_delivery_instruction' => 'string', 'intro_weeks_min' => 'string', 'intro_weeks_using' => 'string', 'intro_weeks_max' => 'string', 'admin_id' => 'string', 'is_terminated' => 'boolean', 'use_new_videos' => 'boolean', 'is_re_open' => 'boolean', 're_open_date' => 'integer', 'opening_soon_message_id' => 'string', 'mindbody_integration' => 'boolean', 'mindbody_signup_step' => 'boolean', 'google_tag_manager_id' => 'string', 'tv_dependency_ids' => 'text', 'glofox_url' => 'string', 'direct_url' => 'string', 'enable_lead_sms_service' => 'boolean', 'enable_lead_email_service' => 'boolean', 'is_add_fb_lead' => 'boolean')





* Visibility: **protected**


### $hasMany

    public mixed $hasMany = array('Equipments' => array('key' => array('id' => 'gym_id')), 'GymIp' => array('key' => array('id' => 'gym_id')), 'GymLogs' => array('key' => array('id' => 'gym_id')), 'Users' => array('key' => 'franchisee_id'), 'FranchiseeEquipmentsLogs' => array('key' => array('id' => 'franchisee_id')), 'FormsOrderEquipments' => array('key' => array('id' => 'franchisee_id')), 'States' => array('key' => array('state' => 'name')), 'FranchiseeReopenLogs' => array('key' => 'franchisee_id'))





* Visibility: **public**


### $hasOne

    public mixed $hasOne = array('Workouts' => array('key' => array('week' => 'week', 'weekday' => 'weekday')), 'License' => array('key' => array('id' => 'franchise_id')), 'EquipmentDetails' => array('key' => array('id' => 'franchisee_id')), 'FranchiseeSettings' => array('key' => array('id' => 'franchisee_id')))





* Visibility: **public**


### $validates

    public mixed $validates = array('name' => array(array('notEmpty', 'message' => 'You must include a name.')), 'week' => array(array('numeric', 'message' => 'Week must be numeric.')), 'weekday' => array(array('numeric', 'message' => 'Day must be numeric.')))





* Visibility: **public**


Methods
-------


### getActiveFranchisees

    mixed app\models\Franchisees::getActiveFranchisees($condition)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $condition **mixed**



### mysql_query

    mixed app\models\Franchisees::mysql_query($sql)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $sql **mixed**



### select_list

    mixed app\models\Franchisees::select_list()





* Visibility: **public**
* This method is **static**.




### get_week_weekday

    mixed app\models\Franchisees::get_week_weekday($id)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id **mixed**



### existence_days

    mixed app\models\Franchisees::existence_days($id)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id **mixed**



### get_countries

    mixed app\models\Franchisees::get_countries()





* Visibility: **public**
* This method is **static**.




### update_ranks

    mixed app\models\Franchisees::update_ranks()





* Visibility: **public**
* This method is **static**.




### get_new_studios_weekly

    mixed app\models\Franchisees::get_new_studios_weekly()





* Visibility: **public**
* This method is **static**.




### get_all_open_studios

    \app\models\[type] app\models\Franchisees::get_all_open_studios()

Return all open studios



* Visibility: **public**




### get_studios_by_div_order_by_distance

    \app\models\[type] app\models\Franchisees::get_studios_by_div_order_by_distance(\app\models\[type] $division_number)

Returns studios order by distance



* Visibility: **public**
* This method is **static**.


#### Arguments
* $division_number **app\models\[type]** - &lt;p&gt;[description]&lt;/p&gt;



### isFunctioning

    mixed app\models\Franchisees::isFunctioning($status_checklist)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $status_checklist **mixed**



### getIsF45TrainingAttribute

    mixed app\models\Franchisees::getIsF45TrainingAttribute($entity)





* Visibility: **public**


#### Arguments
* $entity **mixed**



### getIsMasterAttribute

    mixed app\models\Franchisees::getIsMasterAttribute($entity)





* Visibility: **public**


#### Arguments
* $entity **mixed**



### getIsProdigyAttribute

    mixed app\models\Franchisees::getIsProdigyAttribute($entity)





* Visibility: **public**


#### Arguments
* $entity **mixed**



### isGymExists

    mixed app\models\Franchisees::isGymExists($gymId)





* Visibility: **public**


#### Arguments
* $gymId **mixed**



### opened_studios_this_month

    mixed app\models\Franchisees::opened_studios_this_month()





* Visibility: **public**
* This method is **static**.




### opened_studios_this_month_per_day

    mixed app\models\Franchisees::opened_studios_this_month_per_day()





* Visibility: **public**
* This method is **static**.




### opening_studios_in_three_months

    mixed app\models\Franchisees::opening_studios_in_three_months()





* Visibility: **public**
* This method is **static**.




### opened_studios_by_country_this_month

    mixed app\models\Franchisees::opened_studios_by_country_this_month()





* Visibility: **public**
* This method is **static**.




### opening_studios_by_country_in_three_months

    mixed app\models\Franchisees::opening_studios_by_country_in_three_months()





* Visibility: **public**
* This method is **static**.




### opened_studios_last_three_months

    mixed app\models\Franchisees::opened_studios_last_three_months()





* Visibility: **public**
* This method is **static**.




### opening_studios_next_three_months

    mixed app\models\Franchisees::opening_studios_next_three_months()





* Visibility: **public**
* This method is **static**.




### getTvUpgradeQuery

    mixed app\models\Franchisees::getTvUpgradeQuery($cond, $fields)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $cond **mixed**
* $fields **mixed**



### isTerminatedStudio

    mixed app\models\Franchisees::isTerminatedStudio($studio_id)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $studio_id **mixed**


