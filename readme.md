> unity2018.3.11f1
>
> 使用 *Burst* 需要在 *package manager* 中导入 *Burst* 
>
> 内容来源于: https://www.youtube.com/watch?v=C56bbgtPr_w

---

### 说明

这是个传统的 behavior 中 update, 但是在 update 使用 job system, 所以 update 所在的主线程cpu消耗很少, 都分摊到了 job system 中