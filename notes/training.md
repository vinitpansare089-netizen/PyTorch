                 IMAGE
            [3 × 32 × 32]
                   │
                   ▼
              CONVOLUTION
                   │
             8 learned filters
                   │
                   ▼
          [8 × 32 × 32]
                   │
                   ▼
                 ReLU
                   │
       remove negative activations
                   │
                   ▼
          [8 × 32 × 32]
                   │
                   ▼
               MAXPOOL
                   │
       look at 2×2 regions
                   │
       keep strongest activation
                   │
                   ▼
          [8 × 16 × 16]