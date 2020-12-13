```
fig = plt.figure(figsize=[8, 12])
subplot_counter = 1

for x in range(0, 160, 10):
    fig.add_subplot(4, 4, subplot_counter)
    plt.imshow(vol[x], cmap='gray')
    plt.axis('off')
    plt.tight_layout()
    subplot_counter +=1
plt.show()

```
