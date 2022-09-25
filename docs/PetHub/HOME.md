# PetHub

![diagram](https://www.plantuml.com/plantuml/svg/0/jLN1RXCn4BrNwZ-OY4CgaKOgS4528arIsYfjGfEsuXJDxavIWzTUR6zAGNnCnG49YICNhlannlPkiqaQw06IGtRjD_EUvyquhum5RVDKi5X92roYtjxQtdh4PIpo1DcLjPbvqMngkDwTSdkLHxb1xR0exMwiqcOcGBe43MCJmQDc-rbZu9REJthD58n5JKlZTfbzDoCi4IGueLVMwLuSjVkdmmSGsJo3H3zT47BQRKm8qJ2PvXPDoPVWpEsPTPgz_yApjo0ww9-EMfVTOV-a-q-f_1fSer4fDfulMLIXR3e2KvPu8s0Sg-dVGEFu2kFtVq8P11rVZOMAmN8b_mpLiuNrzo5I9V4cS8v1s5LewLyJv3GNe3VkluCPRDpCbB5JZUQ3s0JPQxgwox8wuTjhlUsVZyQNHwF3SQ_xkdlQgU-uzG6LKicwgrO79v0B-uJLpaq-lzLSrUXvCFyL2RAKdXy7Fr_Ml06rdQNeVcO8tLO28gKXKTe5dw6n5B8M78gqag6Lf5nIaF_b55XcyGjh_Au1QluCmnjghtIyhtAPWBwfGvQvg8nam_pR_AjY0xI7ULJROP-tjnXzGaJz6gFM6lOI8qTwJ2Oma0aR-cAoaujsxKcjAwt6AJ3bhngS_qeKepFERosLY97ic8DWo80D1oqc5OkqkYQrLVN17IVTIRcxLEec0-8Tqfx0nW2co4YSq-KwivHaOiqpImojq4HklHGruy3s0ny3moQvZ2aI14yWGSCofPcS_vYXODGj4ACnYf7-l71xjogowD5rbQcAkC1GjXF_x6Hwc-vNr2hEC5EimAyA4ppb5XAId85sjIqLKP7JF7sOBiYuqp0uscYUQySO8wJYqQMdn0p9i8dIgJF-9nRimJbaTsh3wUu4kE5SO-z4zIGYWdsGr0Pk5gbt3Jj30U6aVfB2v0xVzAhv5lFiidvnQIiztVrewn4b3KTpcQan8AMxLncNSwH1cbB_0PS4HQx1L1bMhYL7KybEOBl8VaPl6WE1hrZbdLqWZmk75ysyV866WQHpBzyerQOvjrpmJ-2o7uv6W-M8uWwu6ymIp2he5MmOcnAubCtVIG_AvP4RCldEAamWnzs_bozDTpWgKtX8KSbx81MGRvFU_3jr6D8iuym3ZplxxGMmL1pq5BEqsFRBeTqtoAcKUoDkU-iLoeJ-8Nu3)

**Level 2: Container diagram**

Once you understand how your system fits in to the overall IT environment, a really useful next step is to zoom-in to the system boundary with a Container diagram. A "container" is something like a server-side web application, single-page application, desktop application, mobile app, database schema, file system, etc. Essentially, a container is a separately runnable/deployable unit (e.g. a separate process space) that executes code or stores data.

The Container diagram shows the high-level shape of the software architecture and how responsibilities are distributed across it. It also shows the major technology choices and how the containers communicate with one another. It's a simple, high-level technology focussed diagram that is useful for software developers and support/operations staff alike.

**Scope**: A single software system.

**Primary elements**: Containers within the software system in scope.
Supporting elements: People and software systems directly connected to the containers.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.

**Notes**: This diagram says nothing about deployment scenarios, clustering, replication, failover, etc.