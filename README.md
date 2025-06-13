graph TD;
    A{Alarm Rings};
    A --> B{Is it the weekend?};
    B --
> Yes --> C(Go back to sleep);
    B -->|No| D{Did I get enough sleep?};
    D -->|Definitely No| E[Snooze button is my best friend];
    E --> A;
    D -->|Surprisingly, Yes| F{Do I *really* need this job?};
    F -->|Yes, bills are real| G[Okay, fine. Coffee first.];
    F -->|No, I'm independently wealthy| H(Go back to sleep, dream of a world without alarms);
    G --> I((Become a functional human... eventually));
