﻿    identity_key = {
        visible = { trigger }		# Determines whether the identity is visible in the list when forming a power bloc.
        possible = { trigger }		# Determines whether the identity is selectable in the list when forming a power bloc.
        can_join = { trigger }		# This trigger is used to check if a country can join a power bloc with this identity. Additional scope details TBD.
        icon = <texture path>		# Icon used to represent this identity
        background = <texture path>	# Background used for power blocs with this identity
        power_bloc_modifier = {}	# This modifier is added to the power bloc
        participant_modifier = {}	# This modifier is added to the leader and every member of the power bloc
        leader_modifier = {}		# This modifier is added to the leader of the power bloc
        member_modifier = {}		# This modifier is added to every member of the power bloc except the leader
        mandate_progress = {}		# This script value is evaluated in the scope of the power bloc to compute the weekly mandate progress value
        cohesion = {}			# This script value computes the cohesion target, which current cohesion drifts towards
    }
