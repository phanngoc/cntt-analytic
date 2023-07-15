
category = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j']

100 x [26 x 10]
26: number of letters in sentence
10: number of categories
100: batch size

[x100
    [x26
        [x10: 0.12, 0.44, 0.55, ....,0.0],  | => 0.12 is the probability of 'a' in the first sentence
        [0.12, 0.44, 0.55, ....,0.0],  | => 0.44 is the probability of 'b' in the first sentence
        [0.12, 0.44, 0.55, ....,0.0],  | => 0.55 is the probability of 'c' in the first sentence
        [0.12, 0.44, 0.55, ....,0.0],  | => 0.0 is the probability of 'j' in the first sentence
        [0.12, 0.44, 0.55, ....,0.0],

    ]
]

----

with attention <class 'tuple'> 12 torch.Size([1, 12, 29, 29])
how to use attention for classification?

----

