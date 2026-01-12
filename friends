## friends

friends/
├── models.py
├── views.py
└── urls.py

friends/models.py

from django.db import models
from django.contrib.auth.models import User

class FriendRequest(models.Model):
    sender = models.ForeignKey(User, on_delete=models.CASCADE, related_name='sent_requests')
    receiver = models.ForeignKey(User, on_delete=models.CASCADE, related_name='received_requests')
    is_accepted = models.BooleanField(default=False)

Friend Suggestions:
Suggest friends-of-friends or users with mutual interests.
suggestions = UserProfile.objects.exclude(user__in=request.user.friends.all())

