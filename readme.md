<p align="center"><img src="https://aloc.ng/asset/images/slide/aloc-shield.png"></p>

<p align="center"><i>Get Inspired to Practice</i></p>

## About ALOC

ALOC is an adventure based CBT practice platform with an engaging game story that unravels as students’ progresses in game levels. We use gaming concepts to increase student practice time and grade.[https://aloc.ng]

- Experience CBT in game environment
- Gain free access to unlimited past questions
- Chat with students across Nigeria
- Get paid for being smart
- Learn for fun, play for glory
  
Finally, boring time are over, academic practice can now be Fun for students seeking university admission.

## About ALOC Questions API

This app gives developers and educator access to our questions via APIs call. You get free access to over 6,000 past questions for UTME, WASSCE, POST-UTME

Make api calls to have access to over 6,000 Major Nigeria past questions. 100% FREE

You can focus on building great apps for students with unlimited access to api calls for trivial questions of major exams in Nigeria

## Our Goal

To have the largest open source database of various past questions in Nigeria. 

## Call for Questions

Over <a href=https://questions.aloc.ng/api/metrics/subjects-call>3,850,863 API questions</a> request has been made to this library. Do you have questions you want to add to this database? We are excited to receive your mail at aloc.mass@gmail.com

## Setup

- `php artisan composer update`

- In the project root directory create another copy of .env.example and rename it to .env

- Generate application key `php artisan key:generate`

- In .env file, supply values to DB_DATABASE, DB_USERNAME, DB_PASSWORD

- `php artisan migrate`

- You can load some dummy data into database for testing `php artisan db:seed --class=LoadDummyQuestions`

- Load report question types `php artisan db:seed --class=ReportQuestionType` this is optional

- `php artisan server` to load app. You Got it!

## API call Examples

Get a question

https://questions.aloc.ng/api/q?subject=chemistry

<img src="https://aloc.ng/asset/images/others/aloc-api-sample.png">

Get many questions (returns 40 questions)

https://questions.aloc.ng/api/m?subject=chemistry

Get several questions (limit 40)

https://questions.aloc.ng/api/q/7?subject=chemistry

eg.

`https://questions.aloc.ng/api/q/23?subject=chemistry`
`https://questions.aloc.ng/api/q/30?subject=chemistry`
`https://questions.aloc.ng/api/q/4?subject=chemistry`


Get a question by year

https://questions.aloc.ng/api/q?subject=chemistry&year=2005

Get a question by exam type

https://questions.aloc.ng/api/q?subject=chemistry&type=utme

Get a question by type and year

https://questions.aloc.ng/api/q?subject=chemistry&year=2010&type=utme

Get question by id and subject

https://questions.aloc.ng/api/q-by-id/1?subject=chemistry

For more detailed examples visit https://questions.aloc.ng
## API Documentation

Vist the <a href='https://github.com/Seunope/aloc-endpoints/wiki'>lib wiki</a> to get access to some special features.<a href='https://github.com/Seunope/aloc-endpoints/wiki'>API Documentation</a>

 
- Subject Metrics
- API Parameters
- Sample APIs
- Subject & Year
  
## ALOC Sponsors

We would like to extend our thanks to the following sponsors for helping fund on-going ALOC development. If you are interested in becoming a sponsor, please send a mail to Admin [aloc.mass@gmail.com]:

- **[MaSSiveTeck](https://magbodo.com/)**

## Contributing

Thank you for considering contributing to the ALOC Questions Api end points!

## Security Vulnerabilities

If you discover a security vulnerability within ALOC APIs, please send an e-mail to Admin via [aloc.mass@gmail.com](mailto:aloc.mass@gmail.com. All security vulnerabilities will be promptly addressed.

## License

The ALOC API is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
