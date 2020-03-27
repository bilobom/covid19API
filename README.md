# covid19API
get covid19 stats in Algeria using ministry of health api 
returns data in one or array as bellow:
eg: /api/covid19/9 returns 
        province: {
            codeName: 9,
            french: "BLIDA",
            arabic: " البليدة"
        },
        deaths: 9,
        recovered: 27,
        activeCases: 140,
        totalConfirmedCases: 176,
        females: 92,
        males: 84,
        lastUpdated: "2020-03-25T23:00:00.000Z",
        ageStatistics: [
            {
                from: 0,
                to: 5,
                count: 2
            },
            {
                from: 5,
                to: 15,
                count: 0
            },
            {
                from: 15,
                to: 25,
                count: 11
            },
            {
                from: 25,
                to: 35,
                count: 24
            },
            {
                from: 35,
                to: 45,
                count: 22
            },
            {
                from: 45,
                to: 60,
                count: 39
            },
            {
                from: 60,
                to: 70,
                count: 36
            },
            {
                from: 70,
                to: 100,
                count: 35
            }
        ]
    }
