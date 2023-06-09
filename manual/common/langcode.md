# Language Codes

## Summary

RAYTeams Service / Client에서 사용하는 Language Code를 정의합니다.

## Language code array
```JSON
export const LANGUAGE = [
	{ code: 'ab', label: 'Abkhazian'},
	{ code: 'aa', label: 'Afar'},
	{ code: 'af', label: 'Afrikaans'},
	{ code: 'ak', label: 'Akan'},
	{ code: 'sq', label: 'Albanian'},
	{ code: 'am', label: 'Amharic'},
	{ code: 'ar', label: 'Arabic'},
	{ code: 'an', label: 'Aragonese'},
	{ code: 'hy', label: 'Armenian'},
	{ code: 'as', label: 'Assamese'},
	{ code: 'av', label: 'Avaric'},
	{ code: 'ae', label: 'Avestan'},
	{ code: 'ay', label: 'Aymara'},
	{ code: 'az', label: 'Azerbaijani'},
	{ code: 'bm', label: 'Bambara'},
	{ code: 'ba', label: 'Bashkir'},
	{ code: 'eu', label: 'Basque'},
	{ code: 'be', label: 'Belarusian'},
	{ code: 'bn', label: 'Bengali (Bangla)'},
	{ code: 'bh', label: 'Bihari'},
	{ code: 'bi', label: 'Bislama'},
	{ code: 'bs', label: 'Bosnian'},
	{ code: 'br', label: 'Breton'},
	{ code: 'bg', label: 'Bulgarian'},
	{ code: 'my', label: 'Burmese'},
	{ code: 'ca', label: 'Catalan'},
	{ code: 'ch', label: 'Chamorro'},
	{ code: 'ce', label: 'Chechen'},
	{ code: 'ny', label: 'Chewa, Chichewa, Nyanja'},
	{ code: 'zh', label: 'Chinese'},
	{ code: 'zh-ans', label : 'Chinese (Simplified)'},
	{ code: 'zh-ant', label : 'Chinese (Traditional)'},
	{ code: 'cv', label: 'Chuvash'},
	{ code: 'kw', label: 'Cornish'},
	{ code: 'co', label: 'Corsican'},
	{ code: 'cr', label: 'Cree'},
	{ code: 'hr', label: 'Croatian'},
	{ code: 'cs', label: 'Czech'},
	{ code: 'da', label: 'Danish'},
	{ code: 'dv', label: 'Dhivehi'},
	{ code: 'nl', label: 'Dutch'},
	{ code: 'dz', label: 'Dzongkha'},
	{ code: 'en', label: 'English'},
	{ code: 'eo', label: 'Esperanto'},
	{ code: 'et', label: 'Estonian'},
	{ code: 'ee', label: 'Ewe'},
	{ code: 'fo', label: 'Faroese'},
	{ code: 'fj', label: 'Fijian'},
	{ code: 'fi', label: 'Finnish'},
	{ code: 'fr', label: 'French'},
	{ code: 'ff', label: 'Fula Pulaar Pular'},
	{ code: 'gl', label: 'Galician'},
	{ code: 'gd', label: 'Gaelic (Scottish)'},
	{ code: 'gv', label: 'Gaelic (Manx)'},
	{ code: 'ka', label: 'Georgian'},
	{ code: 'de', label: 'German'},
	{ code: 'el', label: 'Greek'},
	{ code: 'kl', label: 'Greenlandic'},
	{ code: 'gn', label: 'Guarani'},
	{ code: 'gu', label: 'Gujarati'},
	{ code: 'ht', label: 'Haitian Creole'},
	{ code: 'ha', label: 'Hausa'},
	{ code: 'he', label: 'Hebrew'},
	{ code: 'hz', label: 'Herero'},
	{ code: 'hi', label: 'Hindi'},
	{ code: 'ho', label: 'Hiri Motu'},
	{ code: 'hu', label: 'Hungarian'},
	{ code: 'is', label: 'Icelandic'},
	{ code: 'io', label: 'Ido'},
	{ code: 'ig', label: 'Igbo'},
	{ code: 'id', label: 'Indonesian in'},
	{ code: 'ia', label: 'Interlingua'},
	{ code: 'ie', label: 'Interlingue'},
	{ code: 'iu', label: 'Inuktitut'},
	{ code: 'ik', label: 'Inupiak'},
	{ code: 'ga', label: 'Irish'},
	{ code: 'it', label: 'Italian'},
	{ code: 'ja', label: 'Japanese'},
	{ code: 'jv', label: 'Javanese'},
	{ code: 'kl', label: 'Greenlandic, Kalaallisut'},
	{ code: 'kn', label: 'Kannada'},
	{ code: 'kr', label: 'Kanuri'},
	{ code: 'ks', label: 'Kashmiri'},
	{ code: 'kk', label: 'Kazakh'},
	{ code: 'km', label: 'Khmer'},
	{ code: 'ki', label: 'Kikuyu'},
	{ code: 'rw', label: 'Kinyarwanda (Rwanda)'},
	{ code: 'rn', label: 'Kirundi'},
	{ code: 'ky', label: 'Kyrgyz'},
	{ code: 'kv', label: 'Komi'},
	{ code: 'kg', label: 'Kongo'},
	{ code: 'ko', label: 'Korean'},
	{ code: 'ku', label: 'Kurdish'},
	{ code: 'kj', label: 'Kwanyama'},
	{ code: 'lo', label: 'Lao'},
	{ code: 'la', label: 'Latin'},
	{ code: 'lv', label: 'Latvian (Lettish)'},
	{ code: 'li', label: 'Limburgish ( Limburger)'},
	{ code: 'ln', label: 'Lingala'},
	{ code: 'lt', label: 'Lithuanian'},
	{ code: 'lu', label: 'Luga-Katanga'},
	{ code: 'lg', label: 'Ganda, Luganda'},
	{ code: 'lb', label: 'Luxembourgish'},
	{ code: 'gv', label: 'Manx'},
	{ code: 'mk', label: 'Macedonian'},
	{ code: 'mg', label: 'Malagasy'},
	{ code: 'ms', label: 'Malay'},
	{ code: 'ml', label: 'Malayalam'},
	{ code: 'mt', label: 'Maltese'},
	{ code: 'mi', label: 'Maori'},
	{ code: 'mr', label: 'Marathi'},
	{ code: 'mh', label: 'Marshallese'},
	{ code: 'mo', label: 'Moldavian'},
	{ code: 'mn', label: 'Mongolian'},
	{ code: 'na', label: 'Nauru'},
	{ code: 'nv', label: 'Navajo'},
	{ code: 'ng', label: 'Ndonga'},
	{ code: 'nd', label: 'Northern Ndebele'},
	{ code: 'ne', label: 'Nepali'},
	{ code: 'no', label: 'Norwegian'},
	{ code: 'nb', label: 'Norwegian bokmål'},
	{ code: 'nn', label: 'Norwegian nynorsk'},
	{ code: 'ii', label: 'Nuosu'},
	{ code: 'oc', label: 'Occitan'},
	{ code: 'oj', label: 'Ojibwe'},
	{ code: 'cu', label: 'Old Bulgarian, Old Church Slavonic'},
	{ code: 'or', label: 'Oriya'},
	{ code: 'om', label: 'Oromo (Afaan Oromo)'},
	{ code: 'os', label: 'Ossetian'},
	{ code: 'pi', label: 'Pāli'},
	{ code: 'ps', label: 'Pushto, Pashto'},
	{ code: 'fa', label: 'Persian (Farsi)'},
	{ code: 'pl', label: 'Polish'},
	{ code: 'pt', label: 'Portuguese'},
	{ code: 'pa', label: 'Punjabi (Eastern)'},
	{ code: 'qu', label: 'Quechua'},
	{ code: 'rm', label: 'Romansh'},
	{ code: 'ro', label: 'Romanian'},
	{ code: 'ru', label: 'Russian'},
	{ code: 'se', label: 'Sami'},
	{ code: 'sm', label: 'Samoan'},
	{ code: 'sg', label: 'Sango'},
	{ code: 'sa', label: 'Sanskrit'},
	{ code: 'sr', label: 'Serbian'},
	{ code: 'sh', label: 'Serbo-Croatian'},
	{ code: 'st', label: 'Sesotho'},
	{ code: 'tn', label: 'Setswana'},
	{ code: 'sn', label: 'Shona'},
	{ code: 'ii', label: 'Sichuan Yi'},
	{ code: 'sd', label: 'Sindhi'},
	{ code: 'si', label: 'Sinhalese'},
	{ code: 'ss', label: 'Siswati'},
	{ code: 'sk', label: 'Slovak'},
	{ code: 'sl', label: 'Slovenian'},
	{ code: 'so', label: 'Somali'},
	{ code: 'nr', label: 'Southern Ndebele'},
	{ code: 'es', label: 'Spanish'},
	{ code: 'su', label: 'Sundanese'},
	{ code: 'sw', label: 'Swahili (Kiswahili)'},
	{ code: 'ss', label: 'Swati'},
	{ code: 'sv', label: 'Swedish'},
	{ code: 'tl', label: 'Tagalog'},
	{ code: 'ty', label: 'Tahitian'},
	{ code: 'tg', label: 'Tajik'},
	{ code: 'ta', label: 'Tamil'},
	{ code: 'tt', label: 'Tatar'},
	{ code: 'te', label: 'Telugu'},
	{ code: 'th', label: 'Thai'},
	{ code: 'bo', label: 'Tibetan'},
	{ code: 'ti', label: 'Tigrinya'},
	{ code: 'to', label: 'Tonga'},
	{ code: 'ts', label: 'Tsonga'},
	{ code: 'tr', label: 'Turkish'},
	{ code: 'tk', label: 'Turkmen'},
	{ code: 'tw', label: 'Twi'},
	{ code: 'ug', label: 'Uyghur'},
	{ code: 'uk', label: 'Ukrainian'},
	{ code: 'ur', label: 'Urdu'},
	{ code: 'uz', label: 'Uzbek'},
	{ code: 've', label: 'Venda'},
	{ code: 'vi', label: 'Vietnamese'},
	{ code: 'vo', label: 'Volapük'},
	{ code: 'wa', label: 'Wallon'},
	{ code: 'cy', label: 'Welsh'},
	{ code: 'wo', label: 'Wolof'},
	{ code: 'fy', label: 'Western Frisian'},
	{ code: 'xh', label: 'Xhosa'},
	{ code: 'yi', label:'Yiddish, ji'},
	{ code: 'yo', label: 'Yoruba'},
	{ code: 'za', label: 'Chuang, Zhuang'},
	{ code: 'zu', label: 'Zulu'}
];
```
