# AutomaticResumeChecking
Проектная работа по дисциплине "Технологии разработки программных приложений".

О проекте:

Автоматическая проверка резюме (АПР) представляет собой автоматизированную систему с использованием искусственного интеллекта, которая анализирует резюме кандидатов и определяет их соответствие вакансиям. Система должна проводить анализ текста резюме и сравнивать его с требованиями, указанными в описании вакансии, а затем предоставлять оценку подходит/не подходит для каждого кандидата. Таким образом, предпринимателю будет легче определить, какие кандидаты следует пригласить на собеседование, а какие не соответствуют требованиям компании.

Зависимости проекта:
```
dependencies {
    developmentOnly 'org.springframework.boot:spring-boot-devtools'
    implementation 'org.springframework.boot:spring-boot-starter'    /* Фреймворк для web */
    testImplementation 'org.springframework.boot:spring-boot-starter-test'  
    compileOnly 'org.projectlombok:lombok'                           /* Аннотации для шаблонного кода */
    annotationProcessor 'org.projectlombok:lombok'
    implementation 'org.apache.opennlp:opennlp-tools:1.9.3'          /* Фреймворк для NLP */
}
```

Для запуска приложения необходимо ввести:
```
  cd build/libs
  java -jar AutomaticResumeChecking-1.0-plain.jar
```
