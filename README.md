# drupalup_logexample


System is unusable:
------
\Drupal::logger('my_module')->emergency($message);

Action must be taken immediately:
------
\Drupal::logger('my_module')->alert($message);

Critical conditions:
------
\Drupal::logger('my_module')->critical($message);

Tipical errors, as when the page doesn't load
------
\Drupal::logger('my_module')->error($message);

Exceptional occurrences that are not errors:
------
\Drupal::logger('my_module')->warning($message);

Normal but significant events (e.g. cron execution):
------
\Drupal::logger('my_module')->notice($message);

Interesting events:
------
\Drupal::logger('my_module')->info($message);

Detailed debug information:
------
\Drupal::logger('my_module')->debug($message);
