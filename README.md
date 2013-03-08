MTurk-Post-Word-Script
======================

Shell scripts for posting HITs requesting that users record themselves saying words on Amazon Mechanical Turk

Based on aws-mturk-clt-1.3.1/samples/external_hit

Some commands:

  Load HITs:
  sh loadHits.sh -input ./post_word/external_hit.input -question ./post_word/external_hit.question -properties ./post_word/external_hit.properties -label external_hit

  Get results:
  sh getResults.sh -successfile ./post_word/external_hit.success -outputfile external_hit.results
