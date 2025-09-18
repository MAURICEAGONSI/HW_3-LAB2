# HW_3-LAB2
FEDERICO CIANDRI
AVA DROZNIK
IRANIA MATOS
MAURICE AGONSI

ggplot(d_HHP2020_24, aes(x = Education, fill = Region)) +
  geom_bar(position = "fill") +
  labs(
    title = "Education by Region",
    x = "Education",
    y = "Proportion",
    fill = "Region"
  ) +
  theme_minimal()

Lesson Learnt:
The South has a larger segment in the lower-education categories, but this segment declines as the education level increases.

The Northeast and West portions appear to grow as education increases, most notably at the “college grad” and “advanced degree” levels.

These patterns suggest differences in educational achievement: with a higher proportion of less-educated respondents in the South, and higher proportions of college/advanced degrees in the Northeast and West.

My understanding  is that the composition of education levels is not uniform across regions; there’s a clear shift in which regions dominate as the education level changes.
