# llama2.cpp

## run on mac

```
$ wget https://karpathy.ai/llama2c/model.bin -P out
$ g++ -O3 -o run run.cpp -lm

run.cpp:138:10: warning: 'auto' type specifier is a C++11
      extension [-Wc++11-extensions]
    for (auto &t : tensor) checkpoint_init_tensor(t, file);
         ^
run.cpp:138:18: warning: range-based for loop is a C++11
      extension [-Wc++11-extensions]
    for (auto &t : tensor) checkpoint_init_tensor(t, file);
                 ^
run.cpp:141:10: warning: 'auto' type specifier is a C++11
      extension [-Wc++11-extensions]
    for (auto &t : tensor) checkpoint_init_tensor(t, file);
         ^
run.cpp:141:18: warning: range-based for loop is a C++11
      extension [-Wc++11-extensions]
    for (auto &t : tensor) checkpoint_init_tensor(t, file);
                 ^
4 warnings generated.
$ ./run out/model.bin
 Once upon a time, there was a little girl named Lily. She loved to play dress- with her clothes and hats. One day, she found a mysterious box in her room. She didn't know what it was, but it looked very old and special.
Lily showed the box to her mom and dad. They warned her about the box, but she didn't know that. She felt it on her head and had a fun funny story about the mysterious box. They decided to keep it a secret and told Lily friends the wights robbers.
From that day on, Lily and her friends would play dressed up in their puppets and pretend to be knights. They were a big success, just like Lily was in the box. And they knew that they could have more mysteries as their secret adventures.
<s>
 Lily and Ben were playing with bricks in the kitchen. They liked to build towers and walls with them. They made shapes and letters and letters with bricks.
But then they saw Mom' reading on the clean paper. She sounded happy and tired. Lily and Ben wanted to see what she was doing. They asked their mom,
achieved tok/s: 66.605646
```

## run on linux

```
$ wget https://karpathy.ai/llama2c/model.bin -P out
$ g++ -O3 -o run run.cpp -lm
$ ./run out/model.bin
 One day, a little cat named Dena went to the park. She saw a big tree with a dry, red ball on top. Dena wanted to play with the ball, but it was too high for her.
Dena had a friend named Doggy who lived in the house next door. Max was a small dog who lived next door. Dena really wanted to play with Dena, so she asked her wall to help her get the ball.
Doggy, saw the wall, wanted to help Dena, so he tried to do it too. But Dogena was too big and he got the ball stuck under the curb. Dclena and Doggy were both sad. They could not play with the ball anymore, and the cat was left far behind.
<s>
 One day, a little girl named Lucy went to the park. She saw a big swing and a feel of sand. Lucy sat on the water and felt the sand between her toes. She loved it!
```
